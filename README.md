# Program-to-find-roots-of-quadratic-equation
#include<stdio.h>
void main()
{
int a,b,c,D;
float r1,r2;
printf("enter value of a,b,c :");
scanf("%d%d%d",&a,&b,&c);
D=b*b-4*a*c;
r1=(-b+sqrt(b*b-4*a*c))/2*a;
r2=(-b-sqrt(b*b-4*a*c))/2*a;
if(D>0)
{
printf(" roots are real and unequal");
printf(" roots are %f and %f ",r1,r2);
}
else if(D=0)
{
printf(" roots are real and equal");
printf(" roots are %f and %f ",r1,r2);
}
else 
{
printf(" roots are imaginary");
}
}
