## Program 24 : Write aprogram using string comparison function.
```c
#include<stdio.h>
#include<string.h>
int main()
{
 char a1[]="My name is";
 char a2[]="Arshdeep Kaur";
 if (strcmp(a1,a2)==0)
 {
     printf("string 1 and string 2 are equal");
 }
   else
   {
  printf("string 1 and string 2 are not equal");
   }
       return 0;
}
```
**Output : string 1 and string 2 are not equal**
