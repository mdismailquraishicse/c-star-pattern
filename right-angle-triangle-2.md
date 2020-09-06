# right-angle-triangle-2.md

#include <stdio.h>

int main()
{
    int i,j,rows;
    
    printf("enter no. of rows:");
    scanf("%d",&rows);
    
    for(i=1;i<=rows;i++)
    {
        for(j=1;j<=rows;j++)
        {
        if(j>=rows+1-i)
        printf("*");
        else
        printf(" ");
        }
        printf("\n");
    }
    

    return 0;
}
