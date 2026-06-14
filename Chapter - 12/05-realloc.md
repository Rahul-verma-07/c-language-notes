# realloc()

The `realloc()` function is used to resize an existing memory block.

## Syntax

```c
pointer = (type *) realloc(pointer,
                           new_size);
```

## Example

```c
#include <stdio.h>
#include <stdlib.h>

int main() {

    int *ptr;

    ptr = (int *) malloc(5 * sizeof(int));

    ptr = (int *) realloc(ptr,
                          10 * sizeof(int));

    printf("Memory Resized Successfully");

    free(ptr);

    return 0;
}
```

## Benefits

* Increases memory size
* Decreases memory size
* Avoids creating a new memory block manually

## Use Cases

* Dynamic arrays
* Growing data structures
* Runtime memory management

### Important

Always check whether realloc() returns NULL before using the returned pointer.
