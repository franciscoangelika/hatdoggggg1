// Program #15: Zodiac Sign

#include <iostream>
using namespace std;

int main() {
   int month, day;
   cout<<"Enter the month of your Birthday: ";
   cin>>month;
   cout<<"Enter the day of your Birthday: ";
   cin>>day;
   if(month>=1&&month<=12&&day>=1&&day<=31) {
       if(month>=1&&month<=12&&day>=1&&day<=31) {
           if(month==1&&day>=20&&day<=31||month==2&&day>=1&&day<=18)
               cout<<"Your zodiac sign is Aquarius. \n\n";
           else if(month==2&&day>=19&&day<=28||month==3&&day>=1&&day<=20)
               cout<<"Your zodiac sign is Pisces.\n\n";
           else if(month==3&&day>=21&&day<=31 ||month==4&&day>=1&&day<=19)
               cout<<"Your zodiac sign is Aries. \n\n";
           else if(month==4&&day>=20&&day<=30||month==5&&day>=1&&day<=20)
               cout<<"Your zodiac sign is Taurus. \n\n";
           else if(month==5&&day>=21&&day<=31||month==6&&day>=1&&day<=20)
               cout<<"Your zodiac sign is Gemini.\n\n";
           else if(month==6&&day>=21&&day<=30||month==7&&day>=1&&day<=22)
               cout<<"Your zodiac sign is cancer. \n\n";
           else if(month==7&&day>=23&&day<=31 ||month==8&&day>=1&&day<=22)
               cout<<"Your zodiac sign is Leo.\n\n";
           else if(month==8&&day>=23&&day<=31||month==9&&day>=1&&day<=23)
               cout<<"Your zodiac sign is Virgo.\n\n";
           else if(month==9&&day>=24&&day<=30||month==10&&day>=1&&day<=22)
               cout<<"Your zodiac sign is Libra.\n\n";
           else if(month==10&&day>=23&&day<=31||month==11&&day>=1&&day<=21)
               cout<<"Your zodiac sign is Scorpio. \n\n";
           else if(month==11&&day>=22&&day<=30||month==12&&day>=1&&day<=21)
               cout<<"Your zodiac sign is Sagittarius. \n\n";
           else if(month==12&&day>=22&&day<=31||month==1&&day>=1&&day<=19)
               cout<<"Your zodiac sign is capricorn. \n\n";
       }       
   }else {    
       cout<<"Error: The input is invalid.\n\n";
   }
 }
