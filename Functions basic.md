```c
#include <stdio.h>
void main ()
{
int i ,a, b, n ;
scanf("%d", &n) ;
for (i = 1; i<=n ; i++)
{
scanf (“ %d %d”, &a, &b );
if (a<b)
printf("%d", a) ;
else
(b<a) ? printf("%d \n",b) : printf("equal \n") ;
}
}
```



```c
#include <stdio.h>

int main()
{
int num1,num2,low=0,high=0,temp;
scanf("%d %d",&num1,&num2);
if (num1<num2)
temp=num1;
else
temp=num2;
for (int i = 2; i < temp ; i++)
{
if (num_2 % i == 0 && num1 % i == 0)
{
low=i;
break;
}
}
for (int i = temp; i > 1; i--)
{
if (num2 % i == 0 && num1 % i == 0)
{
high = i;
break;
}
}
if (high !=0 && low !=0)
printf("high %d low %d",high,low);
else
printf("cant find any");
}
```

