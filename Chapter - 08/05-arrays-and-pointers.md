# Arrays and Pointers

The name of an array acts as a pointer to its first element.

## Example

```c
#include <stdio.h>

int main() {

    int arr[] = {1, 2, 3, 4, 5};

    int *ptr = arr;

    for(int i = 0; i < 5; i++) {
        printf("%d ", *ptr);
        ptr++;
    }

    return 0;
}
```

## Equivalent Statement

```c
int *ptr = &arr[0];
```

can also be written as:

```c
int *ptr = arr;
```

## Output

```text
1 2 3 4 5
```
