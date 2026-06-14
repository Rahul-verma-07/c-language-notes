# Reading Files

Files can be read using various functions.

## Example

```c
#include <stdio.h>

int main() {

    FILE *ptr;

    ptr = fopen("sample.txt", "r");

    char ch;

    ch = fgetc(ptr);

    printf("%c", ch);

    fclose(ptr);

    return 0;
}
```

### Purpose

Reads data from a file and displays it on the screen.
