#include<iostream>
#include<ctime>
using namespace std;
//Time Complexity of this function insert is O(n)
void insert(int arr[],int n){
    cout<<"Enter the values in the array :";
    for(int i=0;i<n;i++){
        cin>>arr[i];
    }
    
}
//Time Complexity of this print function is O(n)
void print(int arr[],int n){
    for(int i=0;i<n;i++){
        cout<<arr[i]<<" ";
    }
    cout<<endl;
}
//Each line in this main function take O(1)
int main(){
    clock_t start,end;
    start=clock();
    int n;
    cout<<"Enter the value of n :";
    cin>>n;
    int arr[n];
    insert(arr,n);
    print(arr,n);
    end=clock();
    double time_taken=double(end-start)/double(CLOCKS_PER_SEC);
    cout<<"Time Taken = "<<time_taken<<"Seconds"<<endl;

    return 0;
}
