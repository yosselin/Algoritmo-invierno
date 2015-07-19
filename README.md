#include"stdafx.h"
#include<iostream>
#include"conio.h"

using namespace std;
int MCD(int a, int b);

void main()
{
	int A,B,c;
	cout<<"Ingrese el primer numero: ";
	cin>>A;
	cout<<"Ingrese el segundo numero: ";
	cin>>B;
	c=MCD(A,B);
	cout<<c;

getch();
}
int MCD(int a, int b)
{
	while(a!=b)
	{
		if(a>b)
			a=a-b;
		if(b>a)
			b=b-a;
	
	}
	return a;
}
