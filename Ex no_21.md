# EX 21 C program to calculate the area of a triangle using pointer.
## DATE:
## AIM:
To write a C program to calculate the area of a triangle using pointer.

## Algorithm
. Start. 
2. Declare three variable value of type float. 
3. Prompt the user to enter  values. 
4. Read the values using scanf. 
5. Find the area of triangle using formula 
6. End.   

## Program:
```
/*
C program to calculate the area of a triangle using pointer.
Developed by: Sasi Kumar B
RegisterNumber:  212223060252
*/
#include <stdio.h> 
int main() { 
    float base, height, area; 
    float *pBase = &base, *pHeight = &height; 
    scanf("%f", pBase); 
    scanf("%f", pHeight); 
    area = 0.5 * (*pBase) * (*pHeight); 
    printf("%.2f\n", area); 
} 
```

## Output:

![image](https://github.com/user-attachments/assets/4b79180b-62e3-4c93-b35c-324c49a8120c)


## Result:
Thus the program was executed and the output was verified successfully.
