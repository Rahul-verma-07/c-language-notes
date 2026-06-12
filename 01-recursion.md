# Recursion

Recursion is a programming technique where a function calls itself.

It is commonly used to solve problems that can be broken down into smaller subproblems.

## Definition

A function defined in C can call itself. This process is known as **Recursion**.

## Example

```c
#include <stdio.h>

void display(int n) {

    if(n == 0)
        return;

    printf("%d\n", n);

    display(n - 1);
}

int main() {

    display(5);

    return 0;
}
```

## Output

```text
5
4
3
2
1
```
