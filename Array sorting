#include<stdio.h>
int main()
{
	int size,i,y;
	
	printf("Enter size of the array : ");
	scanf("%d",&size);
	int a[size];
	for(i=0;i<size;i++)
	{
		printf("Enter a number : ");
		scanf("%d",&a[i]);
	}
	for(i=0;i<=size-1;i++)
	{
		for(y=0;y<=size-2;y++)
		{
			int t=0;
			if(a[y]>a[y+1])
			{
				t=a[y];
				a[y]=a[y+1];
				a[y+1]=t;
			}
		}
	}
	printf("Sorrted array is : ");
	for(i=0;i<size;i++)
	{
		printf("\n%d",a[i]);
		printf("\n");	
		
	}
}
