## Program 30: Write a program to display Fibonnaci series.
```c
#include<stdio.h>
int main()
{
	int i,f=0,s=1,t;
	printf("%d%d",f,s);
	for(i=0;i<10;i++)
	{
		t=f+s;
		f=s;
		s=t;
		printf("\n%d",t);
		
	}
	return 0;
}
```
**Output:**
```
01
1
2
3
5
8
13
21
34
55
89
