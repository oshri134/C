```c
#include <stdio.h>
#include <math.h>
int isPrimary(int num);
void main() 
int x;
printf("Enter a number ");
scanf("%d", &x);
if (isPrimary(x) == 1)
printf("The number %d is a primary number",x);
else
printf("The number %d is not a primary number",x);
}
int isPrimary(int num) //
{
for (int i = 2; i <= num/2; i++)
{
if (num%i==0)
{
return 0;
}
}
return 1;
}
```

```c
#include <stdio.h>
#include <math.h>
int isPrimary(int num); //  
void main()
    
int num,i;
printf("Enter a number ");
scanf("%d", &num);
for (int i = 2; i <= num; i++)
{
if (isPrimary(i) == 1)
printf("%d ",i);
}
}
int isPrimary(int num) // 
{
int y = 1;
for (int i = 2; i <= num / 2; i++)
{
if (num % i == 0)
{
y = 0;
break;
}
}
return y;
}
```

