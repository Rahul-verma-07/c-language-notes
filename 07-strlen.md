# strlen()

The `strlen()` function returns the length of a string.

## Syntax

```c
strlen(string_name);
```

## Example

```c
#include <stdio.h>
#include <string.h>

int main() {

    char str[] = "Hello World";

    printf("%d", strlen(str));

    return 0;
}
```

## Output

```text
11
```

### Note

The null character (`\0`) is not counted.
