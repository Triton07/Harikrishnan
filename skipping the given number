write a C program to skip the given number in the given p to q value.

#include<stdio.h>
int main()
{
	int p,q,r,i;
	printf("Enter the value of p = ");
	scanf("%d",&p);
	printf("Enter the value of q = ");
	scanf("%d",&q);
	printf("Enter the value to be skipped = ");
	scanf("%d",&r);
	if(int(p) && int(q))
	{
		for(i=p;i<=q;i++)
		{
			if((i%10==r))
			{
				continue;
			}
      	if((i/10)%10==r)
			{
				continue;
			}
			if((i/100)%10==r)
			{
				continue;
			}
			printf("%d ",i);
		}
	}
	else 
	{
		printf("\nInvalid input");
	}
	
	return 0;
}

test cases: 
case 1:
Enter the value of p = 200
Enter the value of q = 220
Enter the value to be skipped = 5
200 201 202 203 204 206 207 208 209 210 211 212 213 214 216 217 218 219 220

case 2:
Enter the value of p = 100
Enter the value of q = 200
Enter the value to be skipped = 0
111 112 113 114 115 116 117 118 119 121 122 123 124 125 126 127 128 129 131 132 133 134 135 136 137 138 139 141 142 143 144 145 146 147 148 149 151 152 153 154 155 156 157 158 159 161 162 163 164 165 166 167 168 169 171 172 173 174 175 176 177 178 179 181 182 183 184 185 186 187 188 189 191 192 193 194 195 196 197 198 199

case 3:
Enter the value of p = 44A
Enter the value of q = 449
Enter the value to be skipped = 4
Invalid input
