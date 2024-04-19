# pattern-printing
#include <iostream.h>
#include<conio.h>
class patt
{
 int a;
 public:
 void pp()
 {
   cout<<"pattern is : ";
   cout<<"enter the no. of line for pattern";
   cin>>a;
   for(int i =0;i<a;i++)
   {
      for(int j=0;j<i;j++)
        {
           cout<<"*";
                       }
            cout<<"\n";
            }
      cout<<"reverse pattern";
      for(int i =0;i<a;i++)
   {
      for(int j=0;j<a-i+1;j++)
        {
           cout<<"*";
                       }
            cout<<"\n";
            } };
    void main()
    {  
      clrscr();
      patt p;
      p.pp();
      }
   
   
void main()
