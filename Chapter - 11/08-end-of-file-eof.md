# End Of File (EOF)

EOF stands for **End Of File**.

It indicates that there is no more data available in a file.

## Example

```c
#include <stdio.h>

int main() {

    FILE *ptr;

    ptr = fopen("sample.txt", "r");

    char ch;

    while((ch = fgetc(ptr)) != EOF) {

        printf("%c", ch);
    }

    fclose(ptr);

    return 0;
}
```

## Why EOF?

* Detects the end of a file.
* Prevents reading beyond available data.
* Commonly used while reading complete files.

### Note

```c
EOF
```

is a predefined constant available in `stdio.h`.
