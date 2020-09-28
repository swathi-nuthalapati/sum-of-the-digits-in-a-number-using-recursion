# sum-of-the-digits-in-a-number-using-recursion
developed by swathi
#include<stdio.h>
void main()
{
 printf("enter a number:");
 scanf("%d",&num);
 printf("sum of the digits:%d\n",sum(num));
 getch();
}
int sum(int num)
{
 if(num)
 {
  return((num%10)+sum(num/10));
 }
 else
 {
  return 0;
 }
}
