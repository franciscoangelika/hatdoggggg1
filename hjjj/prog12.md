//Program #12: Vote Eligibility Verifier

#inlcude <iostream>
using namespace std;

int main (){ 
  int age;
  cout << "Please enter your age: "; 
  cin >> age;
  if (age > 17)
    cout << " You are eligible to vote. Your age is "<<age<<" years old.\n";
  else
    cout << "Sorry! You are not elgible to vote!";
}    
