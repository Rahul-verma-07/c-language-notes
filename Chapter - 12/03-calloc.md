# calloc()

The `calloc()` function allocates memory for multiple elements and initializes them to zero.

## Syntax

```c
pointer = (type *) calloc(number_of_elements,
                          size_of_each_element);
```

## Example

```c
#include <stdio.h>
#include <stdlib.h>

int main() {

    int *ptr;

    ptr = (int *) calloc(5, sizeof(int));

    for(int i = 0; i < 5; i++) {
        printf("%d ", ptr[i]);
    }

    free(ptr);

    return 0;
}
```

## Output

```text
0 0 0 0 0
```

## Difference from malloc()

| malloc()            | calloc()            |
| ------------------- | ------------------- |
| Garbage values      | Initializes to zero |
| Single memory block | Multiple elements   |
