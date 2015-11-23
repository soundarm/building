#include <stdio.h>
int main()
{
  int num;
  printf("\n enter the numner");
  scanf("%d",&num);
  if(num==0)
    printf("\n THe given number is ZERO");
    else
    {
      if(num<0)
          printf("\n the given number is negative");
          else
          printf("\n the given number is positive");
    }
  return 0;
}
