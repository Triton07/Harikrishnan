Write a program to input and print student data using pointer object of structure.

#include <stdio.h>
struct student {
    char firstName[50];
    int roll;
    float marks;
} ;

int main()
 {
 	struct student std;
 	struct student *ptr;
 	ptr=&std;
    int i,n;
    printf("Enter the total number of student = ");
    scanf("%d",&n);
    for (i = 0; i < n; i++)
	 {
        std.roll = i + 1;
        printf("\n\n");
        printf("Enter first name: ");
        scanf("%s", ptr->firstName);
        printf("Enter marks: ");
        scanf("%f", ptr->marks);
    }
    for (i = 0; i < n; i++) 
	{
        printf("\nRoll number: %d\n", i + 1);
        printf("First name: ");
        puts(std.firstName);
        printf("Marks: %.f", ptr->marks);
        printf("\n");
    }
    return 0;
}
