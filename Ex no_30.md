# EX 30 C program to add two integer elements in an array using realloc() and that array already has three elements.
## DATE:10/04/2025
## AIM:
To write a C program to add two integer elements in an array using realloc() and that array already has three elements.

## Algorithm
1. Start.
2. Declare array size
3. Initialize array elements using malloc()
4. Update array size using realloc()
5. Print the result.
6. End.  

## Program:
```
program to add two integer elements in an array using realloc() and that array already has three elements.
Developed by Karthick Kannan SP
Register number:212222060114
#include <stdio.h>
#include <stdlib.h>
int main() {
 int *arr, size, i;
 size = 3;
 arr = (int *)malloc(size * sizeof(int)); 
 for (i = 0; i < size; i++) {
 arr[i] = i * 10; }
 printf("Original array:\n");
 for (i = 0; i < size; i++) {
 printf("%d ", arr[i]);
 }
 printf("\n");
 size *= 2;
 arr = (int *)realloc(arr, size * sizeof(int)); 
 for (i = size / 2; i < size; i++) {
 arr[i] = i * 10;
printf("Updated array:\n");
 for (i = 0; i < size; i++) {
 printf("%d ", arr[i]);
 }}
```

## Output:
![image](https://github.com/user-attachments/assets/93f656ca-fc92-4131-8081-a7dfaaadb787)



## Result:
Thus the program was executed and the output was verified successfully.
