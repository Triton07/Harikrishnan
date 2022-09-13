Write a C program to find the sum of two numbers using call by reference:

#include <stdio.h>
int addTwo(int *x, int *y)
{
    int sum;
    sum = *x + *y;
    return sum;
}
int main(){
    int a, b, sum;
    int *p, *q;
    printf("Enter the first number: ");
    scanf("%d", &a);
    printf("Enter the second number: ");
    scanf("%d", &b);
	sum = addTwo(&a, &b);
    printf("Sum of the two numbers is: %d", sum);
    
    return 0;
}
Test cases:

case 1:
Enter the value of A = 0
Enter the value of B = 4
The sum of two numbers = 4

Case 2:
Enter the value of A = 5
Enter the value of B = 0
The sum of two numbers = 5

Case 3:
Enter the value of A = -3
Enter the value of B = 3
The sum of two numbers = 0

Case 4:
Enter the value of A = 0
Enter the value of B = 0
The sum of two numbers = 0

Case 5:
Enter the value of A = 123
Enter the value of B = 123
The sum of two numbers = 246
