# calculator

#include <stdio.h> 
int main(void) 
{ 
   int x, y;  
   char z; 
   while (1)  
   { 
      printf("\n*********"); 
      printf("\nA___Add"); 
      printf("\nS___Subtract"); 
      printf("\nM___Multiply"); 
      printf("\nD___Divide"); 
      printf("\nQ___Quit"); 
      printf("\n*********"); 
      do 
      { 
         printf("\n연산을 선택하시오 : "); 
         scanf_s("%c", &z, 1);  /
      }while (z != 'A' && z != 'S' && z != 'M'&& z != 'D' && z != 'Q'); 
      if (z == 'Q') 
      break;   
      printf("두수를 공백으로 분리하여 입력하시오 : "); 
      scanf_s("%d %d", &x, &y); 
      if (z = 'A') 
      printf("연산의 결과는 %d 입니다", x + y);  
      else if (z = 'S') 
      printf("연산의 결과는 %d 입니다", x - y);  
      else if (z = 'M') 
      printf("연산의 결과는 %d 입니다", x*y);    
      else if (z = 'D') 
      printf("연산의 결과는 %d 입니다", x / y);   
      while(getchar()!='\n');   
   } 
   return 0; 
} 
