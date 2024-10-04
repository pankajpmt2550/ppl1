#include<iostream>

using namespace std; 

class pankaj
{
	char name[52];

     int roll;
     char section[23];
     char college[50];
     
	public:
		pankaj()
		{
		
	 
	    cout<<"my name is a = ";
		cin>>name ;
		cout<<"my roll number is = ";
		cin>>roll;
		cout<<" college name is = ";
		cin>>college;
}
	
	void disply()
	{
		cout<<endl<<name<< " \v"<<roll<<"\v"<<college<<endl;
	}
	
	void pa(){ 
	cout<<endl<<name<<"\v"<<roll<<"\v"<<college;
	}
	
};

int main ()
{
	pankaj p1,p2,p3;
	p1.disply();
	p2.pa();
	
}
