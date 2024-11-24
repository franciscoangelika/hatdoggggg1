// Program #17: Letter Verifier
#include <iostream>
using namespace std;

int main() {
    char input;
    cout<<"Enter a character: ";
    cin>>input;
    if((input >= 'a' && input <= 'z')||(input >= 'A' && input <= 'Z'))
        cout<<"You have entered a character.\n";
    else
        cout<<"Invalid input.\n";
}
