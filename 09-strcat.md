# strcat()

The `strcat()` function joins two strings.

## Syntax

```c
strcat(string1, string2);
```

## Example

```c
#include <stdio.h>
#include <string.h>

int main() {

    char str1[20] = "Hello ";
    char str2[] = "World";

    strcat(str1, str2);

    printf("%s", str1);

    return 0;
}
```

## Output

```text
Hello World
```

### Important

Ensure the destination string has enough memory to store the combined result.
