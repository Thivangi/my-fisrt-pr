# my-fisrt-pr
adding information about me
#include <stdio.h>
int main()
int a,b,z,max;
printf("enter 3 numbers");
scanf("%d%d%d",&a,&b,&z);
max=a;
if(b>max)
max=b;
if(z>max)
max=z;
printf("the maximum is %d\n",max);
return 0;
