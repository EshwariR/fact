#include<iostream>
  int fact(int n)
  {
  int f=1;
  if(n==1)
  return 1;
  return n*fact(n-1);
 }
void main()
{
int n=5;
int f=fact(n);
cout<<f;
}          
