# C-program-9
Swapping elements 1

include<stdio.h>
#include<conio.h>
int main()
{
	int a,b,c;
	clrscr();
	printf("elements brfore swappimg:");
	scanf("%d%d",&a,&b);
	c=b;
	b=a;
	a=c;
	printf("elements after swapping:%d\n%d",a,b);
	getch();
	return 0;
 
