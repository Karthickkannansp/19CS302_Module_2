# EX 7 C Program to Print a right triangle star Pattern
## DATE:13/03/2025
## AIM:
To write a C Program to Print a right triangle star Pattern

## Algorithm
1. Start. 
2. Declare the variables i,j,k,n. 
3. Prompt the user to enter a value. 
4. Read the value using scanf. 
5. Enter number of rows and columns. 
6. End.

## Program:
```
Program to Print a right triangle star Pattern
Developed by Karthick Kannan SP
Register number:212222060114
#include <stdio.h> 
int main() { 
    int i, j, rows; 
    scanf("%d", &rows); 
    for (i = 1; i <= rows; i++) { 
        for (j = 1; j <= i; j++) { 
            printf("*"); 
        } 
        printf("\n"); 
    }    return 0; 
}
```
## Output:
![image](https://github.com/user-attachments/assets/6cb7e445-571e-4865-b146-b05ef5c5ec8b)



## Result:
Thus the program was executed and the output was verified successfully.
