## Program 22 : Write a program using string copy function.
```c
#include<stdio.h>
#include<string.h>
int main()
{
    char a[]="My name is";
    char b[]="Arshdeep Kaur";
    strcpy(b,a);
    printf("%s",a);
    printf("\n%s",b);
 return 0;
}
```
**Output:**
```
My name is
My name is
