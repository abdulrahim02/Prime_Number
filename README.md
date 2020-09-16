# Prime_Number
Created by Abdulrahim Mulla


//Prime_Number
#include<stdio.h>
#include<stdlib.h>
int main()
{
	int num,i,j;
	printf("Enter the Number : \n");
	scanf("%d",&num);
	
	for(i=1 ;i<=num/2 ;i++)
	{
		if(num%i == 0)
		{
			j++;
			break;
		}
		i++;
	}
	if(j==0 && num!=1 && num%2==0)
	{
		printf("\n %d is not a Prime Number \n",num);
	}
	else
	{
		printf(" %d is a Prime Number \n",num);
	}
	
	return 0;
}

