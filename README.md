```# Практична 1 
Виконав Печкур Максим

#include <stdio.h>

int main()
{ float ans,t1,t2,t3;
  
    printf("Уведіть t1: ");
    scanf("%f", &t1);
  
    printf("Уведіть t2: ");
    scanf("%f", &t2);
  
    printf("Уведіть t3: ");
    scanf("%f", &t3);
  
  if (t1 >= 10000 || t2 >= 10000 || t3 >= 10000){
       printf ("Error");
       return 0;
   }
  
    ans= ((t1+t2+t3)/3)/3; 
  
    printf("Час необхідний для з'їдання пригода: %.2f", ans);

    return 0;
}
```
