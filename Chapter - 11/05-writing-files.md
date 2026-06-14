# Writing Files

Data can be written into files using file functions.

## Example

```c
#include <stdio.h>

int main() {

    FILE *ptr;

    ptr = fopen("sample.txt", "w");

    fputc('A', ptr);

    fclose(ptr);

    return 0;
}
```

## Result

The character `A` is written into the file.
