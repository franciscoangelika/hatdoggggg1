// Program 7: Fare Calculator

include <iostream>
using namespace std;

int main () {
  float distance;
  float fare;
  cout << "Please enter the total distance of the ride: ";
  cin >> distance;

  if(distance > 4)
    fare = 40.0f + (distance - 4) * 5;
  else
    fare = distance * 10.0f;

  cout << "Your total fare is: " << fare;
}  
