write a C program to find the n and nth prime number.

#include<stdio.h>
int main()
{
	int i,j,N,n=0;
	printf("Enter the value of N : ");
	scanf("%d",&N);
	if(n>0)
	{
	for(i=2;i<=1000;i++)
	{
		int b=0;
		for(j=1;j<i;j++)
		{
			if(i%j==0)
			{
				b++;
			}
		}
		if(b==1)
		{
			n++;
			if(n==N)
			{
				printf("%dth prime number is %d",N,i);
				printf("\n%d prime numbers after %dth prime numbers are ",N,N);
			}
			else if((n>N)&&(n<=N*2))
			{
				printf("%d ",i);
			}
		}
	}
	}
	else 
	{
	printf("Invalid input");
	}
}

Test cases:

Case 1:
Enter the value of N : P
Invalid Input

Case 2:
Enter the value of N : 0
0

Case 3:
Enter the value of N : -4
Invalid input

Case 4:
Enter the value of N : 11
11th prime number is 31
11 prime numbers after 11th prime numbers are 37 41 43 47 53 59 61 67 71 73 79

Case 5:
Enter the value of N : 7.2
Invalid input
