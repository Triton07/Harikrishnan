Write a c Program to print the employee salary,bonus by getting the input as salary:

#include<stdio.h>
int main()
{
	float s,salary,bonus;
	char grade;
	printf("Enter your grade = ");
	scanf("%c",&grade);
	if(grade=='A')
	{
		printf("Enter the salary = ");
		scanf("%f",&salary);
		if(salary>0)
		{
			if(salary>10000)
			{
				bonus=salary*0.5;
				s=salary+bonus;
				printf("The bonus amount = %f",bonus);
				printf("\nThe total amount = %f",s);
			}
			else 
			{
				bonus=salary*0.7;
				s=salary+bonus;
				printf("The bonus amount = %f",bonus);
				printf("\nThe total amount = %f",s);
			}
		}
		else 
		{
			printf("Invalid Input");
		}
	}
	else if(grade=='B')
	{
		printf("Enter the salary = ");
		scanf("%f",&salary);
		if(salary>0)
		{
			if(salary>10000)
			{
				bonus=salary*0.10;
				s=salary+bonus;
				printf("The bonus amount = %f",bonus);
				printf("\nThe total amount = %f",s);
			}
			else 
			{
				bonus=salary*0.10;
				s=salary+bonus;
				printf("The bonus amount = %f",bonus);
				printf("\nThe total amount = %f",s);		
			}
		}
		else 
		{
			printf("Invalid Input");
		}
	}
	else 
	{
		printf("Invalid Input");
	}
	return 0;
}
Test Cases:

Case 1:
Enter your grade = A
Enter the salary = 8000
The bonus amount = 5600.000000
The total amount = 13600.000000

case 2:;
Enter your grade = C
Invalid Input

Case 3:
Enter your grade = B
Enter the salary = 0
The bonus amount = 0.000000
The total amount = 0.000000

Case 4:
Enter your grade = 38000
Invalid Input

Case 5:
Enter your grade = B
Enter the salary = -8000
Invalid Input
