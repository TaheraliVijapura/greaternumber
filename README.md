# greaternumber

#include <stdio.h>
int main()
{
	int a[5],b[5],i;
	for (i=0;i<=5;i++)
	{
		printf("enter the value a \n");
		scanf("%d",&a[i]);
		
			printf("enter the value b \n");
		scanf("%d",&b[i]);
		}	
		for (i=0;i<5;i++)
		{
			if(a[i]>b[i])
			{
				printf("%d is greater %d \n",a[i],b[i]);
			}
			if(b[i]>a[i])
			{
				printf("%d is greater %d \n",b[i],a[i]);
			}
		}
		return 0;
}
