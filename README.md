#include<stdio.h>
int main() 
{
  int i, j, k,m;
  printf("enter the three number") ;
  scanf("%d%d%d", &i, &j, &k) ;
  if(i>j&&i>k) 
  {
    m=i;
  }
  else if(j>k) 
  {
     m=j;
  }
  else 
  {
    m=k;
  }
  printf("bigger number is %d" ) ;
  return (0);
  }
    
