## Program 33 : Write a programe to check palindrome string.
```c
#include<stdio.h>
#include<string.h>
int main()
{
	char string1[25];
	int i,j,k=1,length;
	printf("Enter the word:");
	scanf("%s",&string1);
	length=strlen(string1);
	j=length-1;
	for(i=0;i<length/2;i++,j--)
	{
		if(string1[i]!=string1[j])
		{
			k=0;
			break;
		}
	}
	if(k==1)
	{
		printf("Word is Palindromic");
	}
	else
	{
		printf("Word is not Palindromic");
	}
	return 0;
}
```
 **Output :**
 ```
 Enter the word:oppo
Word is Palindromic
