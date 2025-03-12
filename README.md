# C_7
MAX ELEMENT IN ARRAY
// Online C compiler to run C program online
#include <stdio.h>

int main() 
{
    int n,i,max;
    printf("enter the num of elements:");
    scanf("%d",&n);
    int arr[n];
    printf("enter %d elements:\n",n);
    for(i=0;i<n;i++){
        scanf("%d",&arr[i]);
    }
    max=arr[0];
    for(i=0;i<=n;i++){
        if(arr[i]>max){
            max=arr[i];
        }
    }
    printf("largest element:%d\n",max);
    return 0;
}
