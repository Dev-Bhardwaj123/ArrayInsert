# ArrayQuestions
Tricks to solve questions on arrays

//Insert an element at last of the array
#include<iostream>
using namespace std;

int main(){
	int n;
	cout<<"Enter the sizde of array: ";
	cin>>n;
	int arr[n];
	for(int i=0;i<n;i++){
		cin>>arr[i];
	}
	n=n+1;
	int x;
	cout<<"Enter element to be inserted:";
	cin>>x;
	arr[n-1]=x;
	for(int i=0;i<n;i++)
	{
		cout<<arr[i]<<" ";
	}
	return 0;
}
