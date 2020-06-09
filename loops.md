1A)

```C
#include <stdio.h>

int main()
{
    int num,inSum = 1,sum=0;
    scanf("%d",&num);
    
        for (int i = 1; i < num+1; i++)
        {
           inSum *= num;
        }
        printf("\n%d", inSum);
}
```



1B)

```C
#include <stdio.h>

int main()
{
    int num,sum=0;
    scanf("%d",&num);
    
        for (int i = 1; i<=num; i++)
        {
           sum += (i * i); 
        }
        printf("\n%d", sum);
}

```



2A)

```C
#include <stdio.h>

int main()
{
    int n, cont = 0; 

     scanf("%d", &n); 

        while (n>0 ) 
        {
            n=n/10;
            
            cont++;
        }
    
    printf("%d",cont);
}
```

2 B

```C

#include <stdio.h>

int main()
{
    int n, cont = 0; 

    for (int  i = 1; i <= 10; i++)
    {
        scanf("%d", &n);

        while (n !=0 ) 
        {
            n /= 10;
            cont++;
        }
    }
    printf("%d",cont);
}
```

