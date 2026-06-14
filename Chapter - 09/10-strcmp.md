# strcmp()

The `strcmp()` function compares two strings.

## Syntax

```c
strcmp(str1, str2);
```

## Return Values

| Result   | Meaning                 |
| -------- | ----------------------- |
| 0        | Strings are equal       |
| Positive | First string is greater |
| Negative | First string is smaller |

## Example

```c
#include <stdio.h>
#include <string.h>

int main() {

    int result = strcmp("Deep", "Joke");

    printf("%d", result);

    return 0;
}
```

## Comparison Rule

Comparison is based on ASCII values of characters.
