```
$ git init
Initialized empty Git repository in /Users/skills/Projects/recipe-repository/.git/
```




```C
#include <stdio.h>

int main()
{
	int num1, num2, num3, num4, num5;
	float avg, sum;
	
	printf("Input: ");
	scanf("%d%d%d%d%d", &num1, &num2, &num3, &num4, &num5);
	
	sum = num1 + num2 + num3 + num4 + num5;
//	avg = (float)sum / 5;
	avg = sum / 5;


	
	printf("Output: %.2f", avg);
	
	return 0;
}

//10 25 33 72 37
```

