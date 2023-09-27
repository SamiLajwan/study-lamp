#include<stdio.h> 
 int stack[25],top=-1,x; 
 void push(); 
 int main() 
 { 
         push(); 
         push(); 
         push(); 
         push(); 
         display(); 
         return 0; 
 } 
 void push() 
 { 
     top=top+1; 
     printf("which element to push"); 
     scanf("%d",& x); 
     stack[top]=x; 
 } 
     void display(){ 
  
     for(int i=0;i<top;i++){ 
             printf("%d",stack[i]) 
         } 
 }