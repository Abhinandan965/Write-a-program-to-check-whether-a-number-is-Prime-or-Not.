#include<iostream>
using namespace std;

int main()
{
 int n,i;

 bool  isPrime = true;

 cout<<"Enter a positive integer :";

 cin>>n;

 for(i=2;i<=n/2; ++i)
  {

   if(n%i==0)
     {

          isPrime= false; 
          break;
      }
   }
if(isPrime)
  cout<<"This is a Prime NumberNumber";
else
cout<<"This is not a Prime number "; 
return 0;
}
