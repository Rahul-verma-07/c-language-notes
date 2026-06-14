# free()

The `free()` function releases memory previously allocated using malloc(), calloc(), or realloc().

## Syntax

```c
free(pointer);
```

## Example

```c
#include <stdlib.h>

int main() {

    int *ptr;

    ptr = (int *) malloc(5 * sizeof(int));

    free(ptr);

    return 0;
}
```

## Why Use free()?

* Prevents memory leaks
* Releases unused memory
* Improves program efficiency

### Important

Always free dynamically allocated memory when it is no longer needed.
