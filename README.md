#include<stdio.h>

int power(int base, int exponent)
{
	int i, ans;
	ans = 1;
	for (i = 0; i < exponent; i++)
	{
		ans = ans*base;
	}
	return (ans);
}

void main()
{

int a, b,re;
printf("Enter base: ");
scanf("%d", &a);
printf("\nEnter exponent: ");
scanf("%d", &b);
re = power(a,b);
printf("\n%d to the power %d is %d\n", a,b,re);
}
