// arthmatic
#include <stdio.h>  
#include <conio.h>  
int main ()  
{    
int num1, num2, res;     
float f1, f2, res1;   
double d1, d2, res2;  
printf (" Enter two integer numbers: ");  
scanf ("%d %d", &num1, &num2);  
res = num1 - num2;   
  
printf (" Enter two float numbers: \n ");  
scanf ("%f %f", &f1, &f2);  
res1 = f1 - f2; 
  
printf (" Enter two double data type numbers: \n ");  
scanf ("%lf %lf", &d1, &d2);  
res2 = d1 - d2;  
printf (" The subtraction of two integer numbers: %d \n", res);  
printf (" The subtraction of two float numbers: %f \n ", res1);  
printf (" The subtraction of two double numbers: %lf", res2);  
return 0;  
} 
