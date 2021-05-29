# challengers
#include <stdio.h>
int sum(int n)  {
   if(n!=0)
       return (n%10 + sum(n/10));
   else
       return 0;
}
int main()
{
   int n;
   printf("Input number: ");
   scanf("%d",&n);
   printf("Sum of the digits : %d",n,sum(n));
   return 0;
}
