# codes- currancy converter program in c++



// programmer name : swapnil ingale 

#include <iostream>
using namespace std;

int main() {
  
cout<<"***********currancy conveter*****************"<<endl;

 int x;
 int y; 
 
float a, b, c, d;         /*
    
   a for indian currency.      x and y for selection 
    b for USD currency 
    c for Euro currency 
    d for pound currency
                            */
 
 cout<<"1) IND "<<endl;
 cout<<"2) USD "<<endl;
 cout<<"3) EURO "<<endl;
 cout<<"4) POUND"<<endl;
 
 cout<<"select currancy no. : ";
 cin>>x;
 
 if(x==1){
    cout<<"IND"<<endl; 
    cout<<"enter amount : ";
    cin>>a;
    cout<<a<<endl;
 }else if(x==2){
    cout<<"USD"<<endl;
    cout<<"enter amount : ";
    cin>>b;
    cout<<b<<endl;     
 }else if(x==3){
    cout<<"EURO"<<endl;
    cout<<"enter amount : ";
    cin>>c;
    cout<<c<<endl;
 }else if(x==4){
     cout<<"POUND"<<endl;
     cout<<"enter amount : ";
     cin>>d;
     cout<<d<<endl;
 }else{
    cout<<"select valid currancy."<<endl;
 }
 
 
cout<<endl<<endl;
 cout<<"1) IND "<<endl;
 cout<<"2) USD "<<endl;
 cout<<"3) EURO "<<endl;
 cout<<"4) POUND"<<endl;
 
 cout<<"select currancy no. which do u have convert: ";
 cin>>y;
 cout<<y<<endl;
 
 cout<<endl;
 switch(x*10+y)
{
   case 11 : a=a*1;
             cout<<"amount in INR : ";
             cout<<a<<endl;
   
   break;
   
   case 12 : b=a*0.013;
             cout<<"amount in USD : ";
             cout<<b<<endl;
   
   break;
   
   case 13 : c=a*0.012;
             cout<<"amount in EURO : ";
             cout<<c<<endl;
   
   break;
   
   case 14 : d=a*0.010;
             cout<<"amount in POUND : ";
             cout<<d<<endl;
   
   break;
   
   case 21 : a=b/0.013;
   
             cout<<"amount in INR : "<<a<<endl;
   
   break;
   
   case 22 : b=b*1;
             cout<<"amount in USD : "<<b<<endl;
   
   break;
   
   case 23 : c=b/1.14;
             cout<<"amount in EURO :"<<c<<endl;
   
   break;
   
   case 24 : d=b/1.35;
             cout<<"amount in POUND :"<<d<<endl;
   
   break;
   
   case 31 : a=c/0.012;
             cout<<"amount in INR : "<<a<<endl;
   
   break;
   
   case 32 : b=c*1.14;
            cout<<"amount in USD : "<<b<<endl;
   
   break;
   
   case 33 : c=c*1;
             cout<<"amount in EURO : "<<c<<endl;
   
   break;
   
   case 34 : d=c/1.19;
             cout<<"amount in POUND : "<<d<<endl;
   
   break;
   
   case 41 : a=d/0.010;
             cout<<"amount in INR : "<<a<<endl;
   
   break;
   
   case 42 : b=d*1.35; 
             cout<<"amount in USD : "<<b<<endl;
   
   break;
   
   case 43 : c=d*1.19;
            cout<<"amount in EURO : "<<c<<endl;
   
   break;
   
   case 44 : d=d*1;
            cout<<"amount in POUND : "<<d<<endl;
   
   break;
   
   default : cout<<"SELECTION WRONG"<<endl;
   
    
}
 
 cout<<endl<<endl;
 cout<<"THANKU "<<endl;
 
    return 0;
}
