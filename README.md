#include <stdio.h>
#include <conio.h>
int main ()
{
    int nilai [5],x;
    printf( " memasukkan nilai : \n");
    for (x=0; x<5; x++)
    {
        printf( "nilai angka :");
        scanf("%d",&nilai[x]);
    }
    printf("\n");
    printf("membaca nilai:\n");
    for (x=0;x<5;x++)
    {
        printf("nilai angka : %d",nilai[x]);
    }
    getch();
}
