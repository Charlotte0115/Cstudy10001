#include <stdio.h>

int main(void)
{
    char mark[7][7] = { 0 };
    int i, j;
    for (i = 0; i < 7; i++)
    {
        for (j = 0; j < 7; j++
        {
            if ( i == j ) mark[i][j] = 'A';
        }
    }
    
    return 0;
}
