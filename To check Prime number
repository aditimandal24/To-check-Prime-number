#include<stdio.h>
int isprime(int,int);
int main()
{
int num, prime;
printf("Enter number: ");
scanf("%d",&num);
prime=isprime(num,num/2);
if(prime==1)
{
	printf("%d is a prime number",num);
}
else
{
	printf("%d is not a prime number",num);
}
}
int isprime(int n,int i)
{
	if(i==1)
	return 1;
	else
	{
		if(n%i==0)
		return 0;
		else
		isprime(n,i-1);
	}
}
