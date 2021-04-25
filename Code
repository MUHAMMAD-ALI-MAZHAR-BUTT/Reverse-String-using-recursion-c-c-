//*************** Efficient Learning World ***********************
#include<iostream>
using namespace std;
//Function to reverse string using recursion
void reverse_(string &a , int start , int end)
{
    if(start>end)
    {
        return;
    }
    else
    {
        swap(a[start],a[end]);
        reverse_(a,start+1,end-1);
    }
}
 int main ( )
 {
  string str = "abcde" ; 
  cout<<"Original string : "<<str<<endl;
  reverse_(str ,  0 , str.length() - 1 ) ;
  cout<<"Reversed string : "<<str;
  }
