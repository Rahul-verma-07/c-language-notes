# Strings Using Pointers

Strings can also be stored using character pointers.

## Example

```c
#include <stdio.h>

int main() {

    char *str = "Rahul Verma";

    printf("%s", str);

    return 0;
}
```

## Important Notes

```c
char str[] = "Rahul";
```

Cannot be reassigned directly.

```c
char *ptr = "Rahul";
```

Can point to another string later.

Pointers provide flexible string handling.
