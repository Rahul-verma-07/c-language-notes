# Pointer Arithmetic

Pointer arithmetic allows pointers to move through memory locations.

## Example

```c
#include <stdio.h>

int main() {

    int a = 7;
    int *ptr = &a;

    printf("%p\n", ptr);

    ptr++;

    printf("%p\n", ptr);

    return 0;
}
```

## Operations Allowed

### Increment

```c
ptr++;
```

Moves pointer to the next memory location.

### Decrement

```c
ptr--;
```

Moves pointer to the previous memory location.

### Addition

```c
ptr + n
```

### Subtraction

```c
ptr - n
```

### Pointer Difference

```c
ptr1 - ptr2
```

## Important Notes

* Pointer movement depends on the data type size.
* For an `int` pointer, movement is usually 4 bytes.
* For a `char` pointer, movement is usually 1 byte.
* Pointer arithmetic is widely used with arrays.
