# Strings: Word Counter in a String (Using Function in C)

## 🎯 Aim
To write a C program that counts the total number of words in a given string using a function.

## 🧠 Algorithm

1. **Declare** a character array `a` of size 100, and variables `i` and `count`, initialized to `0` and `1` respectively.
2. **Read** a string (including spaces) until a newline character is encountered and store it in array `a`.
3. **Use** a `do-while` loop to iterate through each character of the string:
   - **Increment** `count` every time a space `' '`, newline `'\n'`, or tab `'\t'` character is encountered.
4. **Print** the final value of `count`, which represents the total number of words in the string.

## Program
```
#include <stdio.h>
void countWords() {
    char a[100];
    int i = 0, count = 1;
    printf("Enter a string: ");
    scanf("%[^\n]", a);
    do {
        if(a[i] == ' ' || a[i] == '\n' || a[i] == '\t') {
            count++;
        }
        i++;
    } while(a[i] != '\0');
    printf("Total number of words = %d\n", count);
}

int main() {
    countWords();  
    return 0;
}
```
## Output
<img width="501" height="303" alt="image" src="https://github.com/user-attachments/assets/d9921c0d-b2d8-4180-a7c8-13747a3908b8" />

## Result
a C program that counts the total number of words in a given string using a function is written.
