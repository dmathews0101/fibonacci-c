
## Printing n numbers of the Fibonacci Series

## C program
```c
// Write a C program to print n numbers 
// of the fibonacci series

#include<stdio.h>    
int main()    
{    
 int i, number1=0,number2=1,number3,n;    
 printf("Enter how many numbers of the fibonacci series to output :");    
 scanf("%d",&n);    
 printf("\n%d %d",number1,number2);   
 for(i=2;i<n;++i)    
 {    
  number3=number1+number2;    
  printf(" %d",number3);    
  number1=number2;    
  number2=number3;    
 }  
  return 0;  
 } 
``` 