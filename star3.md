별찍기 : 입력받은 크기의 다이아몬드 (피라미드의 합)

```c
#include <stdio.h>

int main(void)
{
  int c;
  printf("다이아몬드 크기 : \n");
  scanf("%d",&c);
for(int i=0; i<c; i++)
    {
      for(int j=0; j<c-i; j++)
        {
        printf(" ");
        }
      for(int s=0; s<2*i+1; s++)
        {
          printf("*");
        }
      printf("\n");
    } //피라미드

  for(int t=0; t<2*c+1; t++)
    {
      printf("*");
    }
    printf("\n");
  
for(int i=c; i>0; i--)
    {
      for(int j=0; j<=c-i; j++)
        {
        printf(" ");
        }
      for(int s=0; s<2*i-1; s++)
        {
          printf("*");
        }
      printf("\n");
    } //역 피라미드
    return 0;
}
