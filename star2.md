별찍기2 (피라미드)


```c
#include <stdio.h>

int main() {
    for(int i=0;i<5;i++)
      {
        for(int j=0;j<4-i;j++)
        {
        printf(" ");
        }
        for(int s=0;s<2*i-1;s++)
        {
        printf("*");
        }
        for(int j=0;j<4-i;j++)
        {
        printf(" ");
        }
        printf("\n");
      }
}
