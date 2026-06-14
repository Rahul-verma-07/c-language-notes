# strcpy()

The `strcpy()` function copies one string into another.

## Syntax

```c
strcpy(destination, source);
```

## Example

```c
#include <stdio.h>
#include <string.h>

int main() {

    char source[] = "Hello";
    char target[20];

    strcpy(target, source);

    printf("%s", target);

    return 0;
}
```

## Output

```text
Hello
```
