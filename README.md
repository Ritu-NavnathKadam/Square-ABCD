# Square-ABCD
#include<stdio.h>
void main()
{
int n;
printf("Enter any number ");
scanf("%d",&n);

int a=65;
for(int I=1;I<=n;I++)
{
for (int j=1;j<=n;j++)
{
printf("%c ",a);
a++;
}
printf("\n");
}

}
