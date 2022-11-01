## Program 4 : Write a program for conditional operator
```
# include<stdio.h>
int main()
{
int c,T=95,P=95;
c=(T>80&&P>80)?1000:(P>80)?500:0;
printf("%d",c);
return 0;
}
