#include<stdio.h>
#include<conio.h>
void main()
{
int user,fact=1,i;
printf("Enter the number");
scanf("%d",&user);
for(i=user;i>0;i--)
  {
  fact=fact*i;
  }
  printf("Factorial:%d",fact);
  getch();
}
