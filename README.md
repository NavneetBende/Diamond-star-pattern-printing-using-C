Diamond star pattern printing
For diamond star pattern printing in java programming, we need to use six loops.

The first For loop is outer loop which contain two For loop. first inner For loop is to print  spaces and second inner For loop print the star to make the pyramid of star.

Now the second outer For loop also contain the two For loop, in which the first For loop is to print the spaces and second For loop print start to make the reverse pyramid of star. 

this two opposite pyramid makes a diamond star pattern

diamond star pattern
Write a program to print the following pattern
Enter the number of row 5

    *
   ***
  *****
 *******
*********
 *******
  *****
   ***
    *


Working
Step 1- Declare the for outer loop for the first pyramid

Step 2- Declare the first inner loop inside the first outer loop for printing spaces.

Step 3- Declare the second inner loop inside the first outer loop for printing star.

Step 4- Declare second the outer  for loop for the second reverse pyramid.

Step 5-Declare the first inner loop inside the second outer loop for printing space.

Step 6- Declare the second inner loop inside the second outer loop for printing star.

Step 7 – Stop.

C	JAVA	Python
#include <stdio.h>  
int main()  
{
    int n, i, j;
    printf(“Enter number of rows : “);
    scanf(“%d”,&n);
    for(i=1; i<=n; i++)
    {
        for(j=1;j<=n–i;j++)
        {
            printf(” “);
        }
        for(j=1;j<=i*2–1;j++)
        {
            printf(“*”);
        }
        printf(“\n“);  
    }
    for(i=n–1;i>0;i–)
    {
        for(j=1;j<=n–i;j++)
        {
            printf(” “);
        }
        for(j=1;j<=i*2–1;j++)
        {
            printf(“*”);
        }
        printf(“\n“);
    }
    return 0;
}  
