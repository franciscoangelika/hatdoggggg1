// Program #18: Character Identifier

#include <iostream>
using namespace std;

int main() {
    char input;
    cout<<"Enter a character: ";
    cin>>input;
    
    cout<<"You entered: "<<input<<"\n";
    if(input >= 48 && input <= 57) 
        cout<<"You have entered a number. \n\n";
    else if((input >= 'a' && input <= 'z')||(input >= 'A' && input <= 'Z'))
        cout<<"You have entered a letter. \n\n";
    else
        cout<<"You have entered a special character.\n\n";
 }
