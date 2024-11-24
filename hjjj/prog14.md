// Program #14: Personal Calculator

#include <iostream>
using namespace std;

int main () {
  int number;
  cout << "Enter the number of month: ";
  cin >> number;
  if (number >= 1 && number <=12) {
    if (number ==1)
      cout << "1 is January - The month of new beginnings. \n\n";
    else if (number ==2)
      cout << "2 is February - The month of love. \n\n";
    else if (number ==3)
      cout << "3 is March - The month of graduation. \n\n";
     else if (number ==4)
      cout << "4 is April - The month of summer. \n\n";
     else if (number ==5)
      cout << "5 is May - The month of relaxation. \n\n";
    else if (number ==6)
      cout << "6 is June - The month of classes. \n\n";
    else if (number ==7)
      cout << "7 is July - The month of meeting. \n\n";
    else if (number ==8)
      cout << "8 is August - The month of hardworking. \n\n";
    else if (number ==9)
      cout << "9 is September - The month of exams. \n\n";
    else if (number ==10)
      cout << "10 is October - The month of celebration. \n\n";
    else if (number ==11)
      cout << "11 is November - The month of souls. \n\n";
    else if (number ==12)
      cout << "10 is- The month of giving. \n\n";
} else 
  cout << "Error: The input is invalid. \n\n";
}




      
