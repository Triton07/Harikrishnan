write a C program to find the pythagorus triplet from the given limit.

#include<stdio.h>
int main()
{
int a,b,c,n;
printf("Enter the value of n : ");
scanf("%d",&n);
if(n>0)
{
 	for(a=1;a<=n;a++)
	{
    	for(b=a;b<=n;b++)
		{
        	for(c=b;c<=n;c++)
			{
            	if(c*c==a*a+b*b)
				{
            		printf("(%d , %d , %d) ",a,b,c);	
				}
			}
		}
	}
}
else 
{
	printf("Invalid input");
}
	return 0;
}

Test cases:

case 1:
Enter the value of n : 10
(3 , 4 , 5) (6 , 8 , 10)

case 2:
Enter the value of n : -10
Invalid input

Case 3:
Enter the value of n : 25
(3 , 4 , 5) (5 , 12 , 13) (6 , 8 , 10) (7 , 24 , 25) (8 , 15 , 17) (9 , 12 , 15) (12 , 16 , 20) (15 , 20 , 25)
