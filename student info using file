write a program to read name and roll number of n number of student from user and store then in a file.

#include <stdio.h>
int main() 
{
	char name[50];
	int roll,i,n;
	printf("Enter number of students: ");
	scanf("%d",&n);
	FILE *fptr;
	fptr=(fopen("student.txt","w"));
	for (i=0;i<n;++i) 
	{
		printf("For student%d\nEnter name: ",i+1);
		scanf("%s",name);
		printf("Enter roll number: ");
		scanf("%d",&roll);
		fprintf(fptr,"\nName: %s \nMarks=%d \n",name,roll);
	}
	fclose(fptr);
	return 0;
}
