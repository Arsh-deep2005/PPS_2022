## program 3 : Write a program for 3 numbers using conditional branching
```C
# include<stdio.h>
int main
{
int a=20,b=30,c=40
if((a>b)&&(a>c))
{
printf("a is greater");
}
else if(b>c)
printf("b is greater");
}
else
{
printf("c is greater");
}
return0;
}
output : c is greater
