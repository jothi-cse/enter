#include<stdio.h>
int main()
{
char str[50],temp;
int i=0,j=strlen(str)-1;
while(i<j)
{
temp=str[i];
str[i]=str[j];
str[j]=temp;
i++;
j--;
return 0;
}
