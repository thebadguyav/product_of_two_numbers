#include<stdio.h>
int main()
{
    int a,b; //declaration of two variables whose product is to be performed
    int product=1;
    printf("Enter the first number:");
    scanf("%d",&a);
    printf("Enter the second number:");
    scanf("%d",&b);
    product=a*b; //product of the two numbers performed
    printf("The product of the two numbers is: %d",product);
return 0;
}
