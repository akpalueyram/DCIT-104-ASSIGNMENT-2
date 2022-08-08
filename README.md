#include<iostream>
using namespace std;
int main()
{
  int a = 0;
  int b;
  int sum = 0;
  for(int b = 1;b<=10000;b++)
    {
    if(b % 2 == 0)
    {
    sum = sum + b;
    a++
    }
    }
    int average = sum / a;
    cout<<endl<<"average is"<<average;
   return 0;
}
