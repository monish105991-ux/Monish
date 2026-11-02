#include <stdio.h>
int main()
{
float R1,R2,R3;
float V,R,I
printf(“Enter R1:”);
scanf(“%f”,&R1);
printf(“Enter R2:”);
scanf(“%f”,&R2);
printf(“Enter R3:”);
scanf(“%f”,&R3);
R=1/((1/R1)+(1/R2)+(1/R3));
printf(“Enter Voltage:”);
scanf(“%f”,&V);
I=V/R;
printf(“Enter the current value=%.2f amperes”,I);
return 0;
}



