// Program 5: Parking Fee Calculator

#include <iostream>
using namespace std; 

int main () {
  int exitTime, entryTime, period;
  float charge;
  cout << " Please your entry time: ";
  cin >> entryTime;
  cout << " Please your exit time: ";
  cin >> exitTime;

  period = exitTime - entryTime; 
  if (period > 1)
    charge = (period) + 1;
  else 
    charge = 2;

  cout << " The charge for your parking is " <<charge;
  
}  
