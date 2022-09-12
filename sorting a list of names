Write a c programs that would sort a list of names in alphabetical order ascending or descending:

#include<stdio.h>
#include<string.h>
int main()
{
	char str[100][100],t[100];
	int i,j,n;
	int op;
	printf("enter number of names:");
	scanf("%d",&n);
	printf("enter the option(1.ascending 2.descending):");
	scanf("%d",&op);
	printf("enter names in any order:");
	for(int i=0;i<n;i++)
	{
		scanf("%s",str[i]);
	}
	for(i=0;i<n;i++)
	{
		for(j=i+1;j<n;j++)
		{
			if(strcmp(str[i],str[j])>0)
			{
				strcpy(t,str[i]);
				strcpy(str[i],str[j]);
				strcpy(str[j],t);
			}
		}
	}
	printf("\nnames sorted in alphabetical order:\n\n");
	switch (op)
	{
		case 1:
			for(i=0;i<n;i++)
			{
				printf("%s\n",str[i]);
			}
			break;
		case 2:
			for(i<n;i>=0;i--)
			{
				printf("%s\n",str[i]);
			}
	}
}

Test cases:

sample input:
enter number of names:5
enter the option(1.ascending 2.descending):1
enter names in any order:banana
carrot
radish
apple
jack

names sorted in alphabetical order:

apple
banana
carrot
jack
radish
