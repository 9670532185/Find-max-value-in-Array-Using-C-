# Find-max-value-in-Array-Using-C++-
#include<iostream>
using namespace std;
int main()
{
int n=6;
int arr[n]={2,1,41,5};
int max=0;
for(int i=0;i<n;i++)
{
	if(arr[i]>max)
	{
		max=arr[i];
	}

}
cout<<max;	
}

