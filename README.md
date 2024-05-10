# Addition-of-two-numbers-using-increment-decrement-operator-in-C
In C ,Addition of two numbers is done without using Arithmetic Operator(+).
#include<stdio.h>
int main(){
    int a,b;
    printf("Enter the two numbers:");
    scanf("%d%d",&a,&b);
    while(b>0){
        a++;
        b--;
    }
    printf("Addition of two numbers :%d",a);
    return 0;
}
output:
Enter the two numbers:4 6
Addition of two numbers :10
