# SWISH-online-test
#include<stdio.h>
int main(){
int cost,p,total=0;
scanf("%d %d",&cost,&p);
p=100-p;
while(cost>0)
{
total=total+cost;
cost=(cost*p)/100;
}
printf("%d",total);
return 0;
}
