# area_using_func.c
#include<stdio.h>
void FindArea(float a,float b)
{
    float area=a*b;
    printf("\narea of rectangle is:%f\n",area);
}
int main()
{
    float length,width;
    printf("Emter the length & width of rectangle:\n");
    scanf("%f",&length);
    scanf("%f",&width);

    FindArea(length,width);
    return 0;
}
