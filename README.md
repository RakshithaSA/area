#include <stdio.h>
#define PI 3.14
float area(float);
int main()
{
    float r,area,circumference,res;
    printf("enter the radius : \n");
    scanf("%f",&r);
     res = PI*r*r;
    printf("area of circle : %f",res);
    circum=2*3.14*r;
    printf("circum of circle: %f",circum);

}
float area(float r)
{
    return PI*r*r;
}
float circum(float r)
{
    return 2*3.14*r;
}
