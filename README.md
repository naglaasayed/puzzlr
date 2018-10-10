# puzzle
#include <iostream>
using namespace std;
int main (){
	int x;
	int y;
	int z;
	int A;
	string B;
	int loc;
	int n=0;
	cout<<"enter the size of array you want : ";
	cin>>x;
	string arr[x];
	for(int i=0 ; i<x ; i++){
        cout<<"eneter element : "<<endl;
        cin>>y;
        arr[i]=y;
	}
	cout<<"the arr is :{";
