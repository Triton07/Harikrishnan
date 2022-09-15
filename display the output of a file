write a C program to display the contents of a file.

#include <stdio.h>
#include <stdlib.h> 
int main()
{
	FILE *fptr;
	char filename[100], c;
	printf("Enter the filename to open \n");
	scanf("%s", filename);
	fptr = fopen("student.txt", "r");
	if (fptr == NULL)
	{
		printf("Cannot open file \n");
		exit(0);
	}	
	while (c != EOF)
	{
		printf ("%c", c);
		c = fgetc(fptr);
	}

	fclose(fptr);
	return 0;
}
