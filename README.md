 #include<stdio.h>
 #include<math.h>
 #define PI 1415926535897932384
 void main()
 {
     long double c,a;
     int b,d;
     a=PI;
     printf("enter the number of digits you want=");
     scanf("%d",&b);
     d=pow(10,b);
    c=a/d;
    printf("the answer is %Lf",c);
 }
