
include <iostream>
#include <string>
using namespace std;
 
int main()
 {
       int num;
       cout<<"Enter number between 1 and 10:"; cin>>num;
       if(num>=1 && num<=10)
       {  cout<<"\nYou have entered correct number";
        return 0;
       }
       cout<<"\nNumber not between 1 and 10";
 }
Output:

Enter number between 1 and 10:4
