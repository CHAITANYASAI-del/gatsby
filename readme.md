#include <stdio.h>

int main() 
{
    int a[3][3],b[3][3],c[3][3],d[3][3],i,j ;
    for(i=0;i<3;i++)
      for(j=0;j<3;j++)
      scanf("%d",&a[i][j]);
      
      
    for(i=0;i<3;i++)
      for(j=0;j<3;j++)
      scanf("%d",&b[i][j]);
      
      
      for(i=0;i<3;i++)
      for(j=0;j<3;j++)
      scanf("%d",&c[3][3]);
      
      
    
     
     
     for(i=0;i<3;i++)
      for(j=0;j<3;j++)
      d[i][j]=a[i][j]+b[i][j]+c[i][j] ;
      printf("\n the value of matrixc are : \n");
    for(i=0;i<3;i++)
      {
          for(j=0;j<3;j++)
          
          printf("%5d",d[i][j]);
          printf("\n");
          printf("\n");
      }
	return 0;
}

