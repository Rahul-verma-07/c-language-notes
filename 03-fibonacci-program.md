# Fibonacci Series Using Recursion

The Fibonacci series is a sequence where each number is the sum of the previous two numbers.

## Sequence

```text
0 1 1 2 3 5 8 13 ...
```

## Program

```c
#include <stdio.h>

int fibonacci(int n) {

    if(n == 1 || n == 2)
        return (n - 1);

    return fibonacci(n - 1) + fibonacci(n - 2);
}

int main() {

    int fibo;

    printf("Enter the term: ");
    scanf("%d", &fibo);

    printf("The %dth Fibonacci term is %d",
           fibo,
           fibonacci(fibo));

    return 0;
}
```

## Example

```text
Input : 7
Output: 8
```
