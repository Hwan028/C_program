별 찍기


```c
#include <stdio.h>


  int main(){
for(int i=5;i>0;i--)
{
    for(int j=0;j<=5-i;j++)
    {
	printf("*");
    }
    printf("\n");
}
  } //직각삼각형
  
```C
#include <stdio.h>

int main() {
    for(int i=0;i<5;i++)
    {
      for(int j=0;j<5-i;j++)
      {
        printf("*");
      }
    printf("\n");
    }
  return 0;
} //역직각삼각형
