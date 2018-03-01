# searchnumber1
#include<stdio.h>
void main()
{
  int n,arr[6],i,c=0;
  scanf("%d",&n);
  for(i=0;i<5;i++)
  {
    scanf("%d",&arr[i]);
    if(arr[i]==n)
    {
      c++;
      printf("%d",i);
      break;
    } 
  }
  if(c!=1)
  {
    printf("-1");
  }
}
