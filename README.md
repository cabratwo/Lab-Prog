#include <stdio.h>
int main(){
int n,i,m,cont;
 scanf ("%d",&n);
 char gab,resp;
 scanf("%s",&gab[n]);
 scanf("%s",&resp[n]);
  
  for(i=0;i<n;i++)
  	if(resp[n]==gab[n])
  		cont++;

  printf("%d",cont);
 return 0;
}  	
