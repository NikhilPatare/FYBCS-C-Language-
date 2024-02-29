# FYBCS-C-Language-# #include<stdio.h>
int main()
  {   
    float r,a;  
    float circle(float r);   
    
    printf("Enter radius:");
    scanf("%f",&r);
    
    a=circle(r);
    printf("\n area of circle=%f",a);
  }
  float circle(float r)
  {
    float a=3.14*r*r;
    return a;
  }