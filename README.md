# dqf
This is a test
#include<stdio.h>
void main()
{
 int a,b,sum;
 a=123;b=456;
 sum=a+b;
 printf("sum is %d\n",sum);
}
int main() 
#include<stdio.h>
{
    int i,y,c;
    for (i = 1; i <= 9; i++) 
    {
        for (y = 1; y <= i; y++)
       {
            c = y * i;
            printf("%d*%d=%d", y, i, c);
            printf(" ");
        }
        printf("\n");
    }
    system("pause");
    return 0;
}
