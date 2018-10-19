#include<iostream>
  int fact(int n)
  {
  int f=1;
  for(int i=1;i<=n;i++)
    f=f*i;
  return f;
 }
void main()
{
int n=5;
int f=fact(n);
cout<<f;
}          
