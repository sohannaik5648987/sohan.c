# sohan.c#include<stdio.h>
int main()
{
	int num;
	printf("Enter the number: ");
	scanf("%d\n",&num);
	if(num%3==0)
	{
		printf("%d is divisible by 3",num);
	}
	else
	{
		printf("%d is not divisible by 3",num);
	}
	return 0;
}
