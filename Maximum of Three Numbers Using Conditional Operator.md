# # Maximum of Three Numbers Using Conditional Operator

This repository contains a **C program** that determines the **maximum of three integer values** using the **conditional (ternary) operator**.

## 🎯 Aim

To write a C program that finds the maximum between three integers using the **conditional (ternary) operator**.

## 📋 Algorithm

1. Declare integer variables: `a`, `b`, `c`, and `max`.
2. Prompt the user to enter three integer values (`a`, `b`, `c`).
3. Use nested ternary operators to calculate the maximum:
   ```c
   max = (a > b) ? (a > c ? a : c) : (b > c ? b : c);
4. Display the maximum value.

## Program
```
#include <stdio.h>

int main() {
    int a, b, c, max;
    printf("Enter three integers:\n");
    scanf("%d %d %d", &a, &b, &c);
    max = (a > b) ? (a > c ? a : c) : (b > c ? b : c);
    printf("Maximum value = %d\n", max);

    return 0;
}
```
## Output
<img width="458" height="334" alt="image" src="https://github.com/user-attachments/assets/661ba5c0-fe9b-4fe7-b9d3-4aa8ad0129a2" />

## Result
C program that finds the maximum between three integers using the **conditional (ternary) operator** is written.
