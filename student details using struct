write a program to store information of n students in structure and display it:

#include <stdio.h>
struct student 
{
    char name[50];
    int roll;
    float marks;
} ;
int main() 
{
    int i,n;
    printf("Enter the value of n = ");
    scanf("%d",&n);
    struct student s[n];
    if(n>0)
    {
    	for (i = 0; i < n; i++) 
		{
        	printf("\nroll number= \n");
        	scanf("%d",&s[i].roll);
        	printf("Enter first name: ");
        	scanf("%s", s[i].name);
        	printf("Enter marks: ");
        	scanf("%f", &s[i].marks);
    	}
    	if(s[i].name>0 && s[i].roll<0)
    	{
    		printf("Invalid input");
		}
    	else
   	 	{
    		for (i = 0; i < n; i++) 
			{
        		printf("\nRoll number: %d", s[i].roll);
        		printf("\nFirst name: %s",s[i].name);
        		printf("\nMarks: %.f", s[i].marks);
        		printf("\n");
    		}
    	} 
	}
	else
	{
		printf("Invalid input");
	}
    return 0;
}

Test cases :

case 1:
Enter the value of n = 4

roll number=
1234
Enter first name: hari
Enter marks: 98

roll number=
1233
Enter first name: krish
Enter marks: 95

roll number=
1253
Enter first name: krishnan
Enter marks: 90

roll number=
2122
Enter first name: hk
Enter marks: 95

Roll number: 1234
First name: hari
Marks: 98

Roll number: 1233
First name: krish
Marks: 95

Roll number: 1253
First name: krishnan
Marks: 90

Roll number: 2122
First name: hk
Marks: 95

Case 2:
Enter the value of n = A
Invalid input
