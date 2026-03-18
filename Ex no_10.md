# EX 10 C program to find the factorial of a given number using a function with arguments and return type.
## DATE:
## Aim:
To write a C program to find the factorial of a given number using a function with arguments and return type.

## Algorithm:
1. Start  
2. Declare function `factorial(int n)`  
3. Initialize `fact = 1`  
4. Loop from `i = 1` to `n`  
5. Multiply `fact = fact * i`  
6. Return `fact`  
7. In `main()`, declare `num`  
8. Read `num` from user  
9. Call `factorial(num)` and store in `result`  
10. Print `result`  
11. End 

## Program:
```
developed by kalaivani P
212222060104
#include <stdio.h>
int factorial(int n)
{
    int fact = 1;
    for (int i = 1; i <= n; ++i)
    {
        fact *= i;
    }
    return fact;
}
int main()
{
    int num;
    printf("Enter a number: ");
    scanf("%d", &num);
    int result = factorial(num);
    printf("Factorial of %d is %d\n", num, result);
    return 0;
}
```
## Output:
![Screenshot 2025-05-06 191334](https://github.com/user-attachments/assets/9f7cc8d2-6f98-4b02-b1b5-177c0a69fa1c)

## Result:
Thus the program was executed and the output was verified successfully.
