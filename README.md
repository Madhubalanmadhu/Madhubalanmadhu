#include <stdio.h>
 
int main()
{
   int m, n, c, d, first[10][10], second[10][10], sum[10][10];
   printf("madhubalan I\n192321142\n");
   printf("Enter the number of rows and columns of matrix\n");
   scanf("%d%d", &m, &n);
   printf("Enter the elements of first matrix\n");
 
   for (c = 0; c < m; c++)
      for (d = 0; d < n; d++)
         scanf("%d", &first[c][d]);
 
   printf("Enter the elements of second matrix\n");
 
   for (c = 0; c < m; c++)
      for (d = 0 ; d < n; d++)
         scanf("%d", &second[c][d]);
   
   printf("Sum of entered matrices:-\n");
   
   for (c = 0; c < m; c++) {
      for (d = 0 ; d < n; d++) {
         sum[c][d] = first[c][d] + second[c][d];
         printf("%d\t", sum[c][d]);
      }
      printf("\n");
   }
 
   return 0;
}![IMG-20231220-WA0007](https://github.com/Madhubalanmadhu/Madhubalanmadhu/assets/154415790/6f9c25db-0977-459c-bf4a-877066ef899e)
