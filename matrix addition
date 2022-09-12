Write a C program to print the matrix addition,get the inputs from the user.

#include<stdio.h>
int main()
{
	int r,c,a[100][100],b[100][100],sum[100][100],i,j;
	printf("Enter the value of rows= ");
	scanf("%d",&r);
	printf("Enter the value of columns= ");
	scanf("%d",&c);
	printf("\nEnter the value of first matrix:\n");
	for(i=1;i<=r;i++)
	{
		for(j=1;j<=c;j++)
		{
			printf("Elements of First matrix:");
			scanf("%d",&a[i][j]);
		}
	}
	printf("\nEnter the value of second matrix:\n");
	for(i=1;i<=r;i++)
	{
		for(j=1;j<=c;j++)
		{
			printf("Elements of Second matrix:");
			scanf("%d",&b[i][j]);
		}
	}
	printf("The Sum of the matrix\n:");
	for(i=1;i<=r;i++)
	{
		for(j=1;j<=c;j++)
		{
			sum[i][j]=a[i][j]+b[i][j];
			printf("%d\t",sum[i][j]);
		}
		printf("\n\n");
	}
	return 0;
}

test cases:

case 1:
Enter the value of rows= 2
Enter the value of columns= 2

Enter the value of first matrix:
Elements of First matrix:1
Elements of First matrix:2
Elements of First matrix:3
Elements of First matrix:4

Enter the value of second matrix:
Elements of Second matrix:1
Elements of Second matrix:2
Elements of Second matrix:1
Elements of Second matrix:2
The Sum of the matrix
:2      4

4       6
