## Program 24: Write a code using strcat.
```
#include<stdio.h>
#include<string.h>
int main()
{	
char a[20]= "The fox";
char b[20]= " jumped";
strcat(a,b);
printf("%s",a);
return 0;
}
```
**Output**: The fox jumped