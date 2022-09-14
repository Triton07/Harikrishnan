Write a C program to find the total and percentage of a student and display it.

#include<stdio.h>
struct student
{
	int tot;
	float per;
	char name[20];
}s;
int main()
{
	int m1,m2,m3,roll;
	printf("enter your roll number = ");
	scanf("%d",&roll);
	if(roll>0)
	{
		printf("Enter your name = ");
		scanf("%s",s.name);
		printf("Enter the mark of m1 = ");
		scanf("%d",&m1);
		printf("Enter the mark of m2 = ");
		scanf("%d",&m2);
		printf("Enter the mark pf m3 = ");
		scanf("%d",&m3);
		s.tot=m1+m2+m3;
		s.per=s.tot/3;
		printf("The total mark = %d",s.tot);
		printf("\nthe percentage = %f",s.per);	
	}
	else 
	{
		printf("Invalid input");
	}
	return 0;
}

Test cases:

Case 1:

enter your roll number = 24
Enter your name = AA
Enter the mark of m1 = 77
Enter the mark of m2 = 65
Enter the mark pf m3 = 75
The total mark = 217
the percentage = 72.000000

Case 2:

enter your roll number = 22
Enter your name = BB
Enter the mark of m1 = 56
Enter the mark of m2 = 62
Enter the mark pf m3 = 50
The total mark = 168
the percentage = 56.000000

Case 3:

enter your roll number = 25
Enter your name = annie
Enter the mark of m1 = 55
Enter the mark of m2 = 65
Enter the mark pf m3 = 74
The total mark = 194
the percentage = 64.000000
