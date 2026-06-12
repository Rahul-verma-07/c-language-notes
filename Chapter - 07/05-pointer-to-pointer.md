# Pointer To Pointer

A pointer can also store the address of another pointer.

This is called a **Pointer to Pointer**.

## Example

```c
#include <stdio.h>

int main() {

    int i = 7;
    int *j = &i;
    int **k = &j;

    printf("%d\n", i);
    printf("%d\n", *j);
    printf("%d\n", **k);

    return 0;
}
```

## Memory Representation

```text
i  → 7
j  → address of i
k  → address of j
```
