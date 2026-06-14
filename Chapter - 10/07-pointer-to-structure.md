# Pointer to Structure

Pointers can store the address of a structure variable.

## Example

```c
#include <stdio.h>

struct employee {
    char name[30];
    int age;
};

int main() {

    struct employee e1 = {
        "Rahul",
        21
    };

    struct employee *ptr = &e1;

    printf("%s", (*ptr).name);

    return 0;
}
```

## Purpose

Allows efficient access to structure members without copying data.
