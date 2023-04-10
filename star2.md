별찍기2 (피라미드)


```c
#include <stdio.h>

int main() {
    for(int i=0;i<5;i++)
      {
        for(int j=0;j<5-i;j++)
        {
        printf(" ");
        }
        for(int s=0;s<2*i-1;s++)
        {
        printf("*");
        }
        for(int j=0;j<5-i;j++) //공백은 앞에만 있으면 되니 어차피 안써도 됐던거였음 뒤에 
        {
        printf(" ");
        }
        printf("\n");
      }
}

