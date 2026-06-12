# Pointers

A pointer is a variable that stores the memory address of another variable.

## Example

```c
#include <stdio.h>

int main() {

    int a = 5;
    int *b = &a;

    printf("Address of a: %p\n", &a);
    printf("Address stored in b: %p\n", b);
    printf("Value of a: %d\n", *b);

    return 0;
}
```

## Why Use Pointers?

* Dynamic Memory Allocation
* Call by Reference
* Efficient Array Handling
* File Handling
* Data Structures
