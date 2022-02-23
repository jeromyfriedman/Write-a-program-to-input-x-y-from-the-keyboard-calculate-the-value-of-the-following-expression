# Write-a-program-to-input-x-y-from-the-keyboard-calculate-the-value-of-the-following-expression
S = 2 x2 y + 1 -|x-1| if x > y           = 5 x – 3 y3 x if x&lt;=y
#include<stdio.h>
#include<conio.h>
#include<math.h>
main()
{
    float  x,y,s=0;
    printf("Nhap x=");
    scanf("%f",&x);
    printf("\nNhap y=");
    scanf("%f",&y) ;    
    if(x>y)
    {
        s=2*x*x*y +1-fabs(x-1) ;    
    }    
    else
    {
        s=5*x - 3*x*pow(y,3);
    }         
    printf ("\n gia tri tinh duoc la  %f",s);
    getch();
}
