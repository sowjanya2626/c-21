# c-21
Reverse right triangle 
#include <stdio.h>
int main() 
{
    int i,j,n,k;
    printf("enter the row of the matrix:");
    scanf("%d",&n);
    for(i=1;i<=n;i++){
        for(j=1;j<=n-i;j++){
                printf("  ");
    }
    for(k=1;k<=i;k++){
        printf("* ");
    }
        printf("\n");
    }
    return 0;
}
