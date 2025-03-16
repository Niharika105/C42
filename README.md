# C42
Swaping 
#include<stdio.h>
void swap(int *a, int *b){
    int c=*a;
    *a=*b;
    *b=c;
    }
int main(){
    int a,b;
    printf("enter the value of a:");
    scanf("%d",&a);
    printf("enter the value of b:");
    scanf("%d",&b);
    printf("before swaping : a = %d, b = %d\n",a,b);
    swap(&a,&b);
    printf("after swaping:a = %d,b = %d\n",a,b);
    return 0;
     }
