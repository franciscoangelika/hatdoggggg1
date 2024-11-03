//Program #6: Average Mark Calculator 

#include <iostream>
using namespace std;

int main () {
  int markA, markB, markC, totalSum;
  float averageMark;
  cout << "Please enter the mark of the first student: ";
  cin >> markA;
  cout << "Please enter the mark of the second student: ";
  cin >> markB;
  cout << "Please enter the mark of the third student: ";
  cin >> markC;
  totalSum = markA + markB + markC;
  averageMark = (float)totalSum / 3; 
  cout << "The average mark of the three students is "<<averageMark;
}  
