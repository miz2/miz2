#include <stdio.h>
#include <conio.h>
int main(){
    int rows,i,j,number=1;
    printf("Enter Number of Rows:");
    scanf("%d",&rows);
    for (i=1;i<=rows;i++){
        for (j=1;j<=i;j++){
            printf("%d ",number);
            number++;
        }
        printf("\n");
    }
}
