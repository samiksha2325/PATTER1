5
44
333
2222
11111

#include<stdio.h>
#include<Conio.h>
void main()
{
clrscr();
int i,j;
for(i=5;i>=1;i++)
{
for(j=5;j>=i;j--)
{
printf("*");
}
printf("\n");
}
getch();
}
