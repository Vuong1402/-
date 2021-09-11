# -#include <stdio.h>
#include <iostream>
using namespace std;
int main()
{
	int a, b, c, d;
	printf("Enter 2 intergers numbers, a>b: ");
	printf("\n a= ");
	scanf("%d", &a);
	printf("\n b= ");
	scanf("%d", &b);
	
	int sum = a+b;
	printf("\n %d + %d = %d", a, b, sum);

	int sub = a-b;
	printf("\n %d - %d = %d", a, b, sub);
	
	float e;
	printf("\n (%d+ %d)/2 = %e", sum, sub);
	
	int mul = a*b;
	printf("\n %d * %d = %d", a, b, mul);

	int div = a/b;
	printf("\n %d / %d = %d", a, b, div);
	
}
