# EX 28 C program that demonstrates the use of enum (enumeration) type to define and use named integer constants.
## DATE:10/04/2025
## AIM:
To write a C program that demonstrates the use of enum (enumeration) type to define and use named integer constants.

## Algorithm
1. Start.
2. Declare enum type
3. Declare all days in a week
4. Print result
5. End

## Program:
```
To write a C program that demonstrates the use of enum (enumeration) type to define and use named integer constants.
Developed by Karthick Kannan SP
Register number:212222060114
#include <stdio.h>
enum weekdays {
 Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday
};
int main() {
 enum weekdays today = Wednesday;
 if (today == Wednesday) {
 printf("Today is Wednesday.\n");
 }
}
```

## Output:
![image](https://github.com/user-attachments/assets/bfe0b197-65b1-493e-80da-2aed386179f4)



## Result:
Thus the program was executed and the output was verified successfully.
