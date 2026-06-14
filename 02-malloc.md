# malloc()

The `malloc()` function allocates a block of memory during runtime.

## Syntax

```c
pointer = (type *) malloc(size_in_bytes);
```

## Example

```c
#include <stdio.h>
#include <stdlib.h>

int main() {

    int *ptr;

    ptr = (int *) malloc(5 * sizeof(int));

    if(ptr == NULL) {
        printf("Memory Allocation Failed");
        return 1;
    }

    printf("Memory Allocated Successfully");

    free(ptr);

    return 0;
}
```

## Features

* Allocates a single block of memory
* Memory contains garbage values initially
* Returns NULL if allocation fails
