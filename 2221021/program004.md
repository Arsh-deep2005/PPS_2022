## Program 4 : Write a program for conditional operator
```C
# include<stdio.h>
int main()
{
int c,T=95,P=95;
c=(T>80&&P>80)?1000:(P>80)?500:0;
printf("%d",c);
return 0;
}
```
**Output: 1000**
