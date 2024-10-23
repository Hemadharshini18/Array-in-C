
#include <stdio.h>

int main()
{
   int r,c;
   scanf("%d %d",&r,&c);
   int x[r][c];
  for(int a=0;a<r;a++){
      for(int b=0;b<c;b++)
      {
      scanf("%d",&x[a][b]);
 
      }
  }
  for(int a=0;a<r;a++)
   {
       for(int b=0;b<c;b++)
       {
           printf("%d",x[a][b]);
       }
       printf("\n");
   }
}
