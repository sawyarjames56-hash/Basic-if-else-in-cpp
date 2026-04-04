#include <iostream>
using namespace std;
int main() {
    int a,b,c,d,e;
    cout<<"enter the number";
    cin>>a>>b>>c>>d>>e;
   int smallest,largest;
   if (a<=b && a<=c && a<=d && a<=e){
       cout<<"smallest"<<a<<endl;
   }else if(b<=a && b<=c&& b<=d && b<=e){
        cout<<"smallest"<<b<<endl;
   }else if(c<=a&& c<=b && c<= d && c<=e){
       cout<<"smallest"<<c<<endl;
   }else if(d<=a && d<=b && d<=c && d<=e){
        cout<<"smallest"<<d<<endl;
   } else {
    cout<<"smallest"<<e<<endl;
   }
   
   if (a>=b && a>=c&& a>=d && a>=e){
       cout<<"largest"<<a<<endl;
   }else if(b>=a && b>=c&& b>=d && b>=e){
        cout<<"largest"<<b<<endl;
   }else if(c>=a && c>=b && c>=d && c>=e){
       cout<<"largest"<<c<<endl;
   }else if (d>=a &&d>=b&& d>=c && d>=e){
      cout<<"largest"<<d<<endl;
    }else {
          cout<<"largest"<<e<<endl;
}
     
     
     
   return 0;
   }
