# my-fisrt-pr
adding information about me
#include <stdio.h>
int main()
int a,b,c,max;
printf("enter 3 numbers");
scanf("%d%d%d",&a,&b,&c);
max=a;
if(b>max)
max=b;
if(c>max)
max=c;
printf("the maximum is %d\n",max);
return 0;
