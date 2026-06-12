# Function Call

A function call tells the compiler to execute a function.

## Example

```c
sum(5, 10);
```

## Complete Program

```c
#include <stdio.h>

int sum(int x, int y) {
    return x + y;
}

int main() {
    int result = sum(5, 10);

    printf("%d", result);

    return 0;
}
```

### Important Points

* Program execution starts from `main()`.
* A program can contain multiple functions.
* Every function is called directly or indirectly from `main()`.
