# Strings

A string is a one-dimensional character array terminated by a null character (`\0`).

## Example

```c
char str[] = "Hello";
```

## Characteristics

* Stored in contiguous memory locations.
* Ends with a null character (`\0`).
* Used to store text data.

## Example Program

```c
#include <stdio.h>

int main() {

    char str[5] = {'R', 'A', 'H', 'U', 'L'};

    for(int i = 0; i < 5; i++) {
        printf("%c", str[i]);
    }

    return 0;
}
```
