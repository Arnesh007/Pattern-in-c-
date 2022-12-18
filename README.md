/*# Pattern-in-c++

QUESTION:

Write a program to print the following pattern.

Sample input:

5

Sample output:

ABCDE

 ABCD

  ABC

   AB

    A        */
    
ANSWER:
#include<iostream>
using namespace std;
int main()
{
     int i,j,n,n1=65;
     cin>>n;
     for(i=0;i<=n;i++)
     { 
         for(j=1;j<=i;j++)
         {
             cout<<" ";
         }
        
         for(j=0;j<n-i;j++)
         {
             
             cout<< char(n1+j);
         }cout<<endl;
     }
     return 0;
}
