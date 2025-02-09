#include<stdio.h>
#include<stdlib.h>
int main()
{
    int a,b;
    printf("Enter the values of a & b :");
    scanf("%d %d",&a,&b);
    int max=((a+b) + abs(a-b))/2;
    int min=((a+b) - abs(a-b))/2;
    printf("The minimum value is %d\n",min);
    printf("The maximum value is %d\n",max);
    return 0;
}
