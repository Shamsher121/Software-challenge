Software-challenge
==================
#include "stdafx.h"
#include "std_lib_facilities.h"
using namespace std;



int main(){

int base;
int height;
int length;
//int area = base*length;

cout<<endl<<"Please enter the base length of the room (CM) ";
cin>>base;

cout<<"Please enter the height of the room (CM) ";
cin>>height;

cout<<"Please enter the length across of the room (CM) ";
cin>>length;

cout<<endl<<"The area of the floor is "<<base*length<<"cm2"<<endl;
cout<<"The volume of the room is "<<base*length*height<<"cm3"<<endl;
cout<<"To paint all the walls you will require enough paint to cover "<<base*length*4<<" cm2 area"<<endl;

	system("pause");

}

