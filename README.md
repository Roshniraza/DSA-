# DSA-
I AM UPLOADING MY DSA TASK
TASK NO.01
#include<iostream>
using namespace std;
int main(){
	int arr[5]={2,4,5,5,5};
	int *ptr=arr;
	for(int i=0;i<5;i++){
		cout<<*ptr<<endl;
		ptr++;
	}
	return 0;
}


 
Task no.02
#include<iostream>
using namespace std;
 
void swap (int* a, int* b){

	int c=*a;
	 *a = *b;
	 *b=c;
	
}
int main(){
	int n1=5;
	int n2=7;
	cout<<"before swap"<<n1<<" "<<n2<<endl;
	swap(&n1,&n2);
cout<<"after swap"<<n1<<" "<<n2;
	return 0;
}
 
