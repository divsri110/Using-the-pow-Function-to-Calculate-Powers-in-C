# Using-the-pow-Function-to-Calculate-Powers-in-C
This program demonstrates the use of the pow() function from the math.h library to calculate exponents. It computes 3.0 raised to the power 2.0 and stores the result in a float variable a, which is then displayed using printf() with the %f format specifier.
#include <stdio.h>
#include <math.h>
int main (){
    float a;
    a= pow(3.0,2.0);
    printf("%f", a);
    return 0;
}
