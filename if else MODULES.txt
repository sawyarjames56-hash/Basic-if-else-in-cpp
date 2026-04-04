#include<iostream>
using namespace std;
int main()
{
	int num1,num2,num3;
	cout<<"Enter three integers: ";
	cin>>num1>>num2>>num3;
	if(num3%num1==0)
	 cout<<"First numnber is factor of third number"<<endl;
	else
	 cout<<"First number is not a factor of third number"<<endl;
	
	if(num3%num2==0)
	 cout<<"Second numnber is factor of third number"<<endl;
	else
	 cout<<"Second number is not a factor of third number"<<endl;
	 
}
