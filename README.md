# fahrenheit-converter
#include<stdio.h>
int main ()
{
    float celcius,fahrenheit;
    printf("fill in the temperature in fahrenheit \n ");
    scanf("%f",&fahrenheit);
    celcius = (fahrenheit- 32)/1.8;
    printf("the temperature in degrees celcius = %f\n",celcius);
    return 0;



}
