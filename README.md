#include <stdio.h>
void main()
{
    int num;
    printf("ENTER A NUM");
    scanf("%d",&num);
    (num%2==0)?printf("num is even"):printf("num is odd");
    
      }

/*even &odd by if else statement*/

#include<stdio.h>
void main()
{
    int num;
    printf(" enter a number ");
    scanf("%d",&num);
    if(num%2==0)
    {
        printf(" even number");
        
    }
    else
    {
        printf("odd number");
    }
}
