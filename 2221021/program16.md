## Program 16 : Write a program to display ages .
```c
#include <stdio.h>
int main() 
{
    float age1;
    double age2;
    printf("Please enter your age:");
    scanf("%f",&age1);
    printf("Enter your child age:");
    scanf("%lf",&age2);
    printf("\nage1=%f",age1);
    printf("\nage2=%lf",age2);
    return 0;
}
```
**Output:**
```
Please enter your age:45
Enter your child age:19
age1=45.000000
age2=19.000000
