# 1.5
/*A program to print a the table in reverse order, 300 to 0*/

#include <stdio.h>

main()
{
    int far;

    for (far=300; far>=0; far=far-20)
    {
        printf("%3d %6.1f\n",far,5.0/9.0*(far-32));
    }
}
