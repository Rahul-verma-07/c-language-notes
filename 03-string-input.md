# String Input

The `scanf()` function can be used to take string input from the user.

## Example

```c
#include <stdio.h>

int main() {

    char str[20];

    scanf("%s", str);

    printf("%s", str);

    return 0;
}
```

## Important Notes

* `scanf()` automatically adds `\0`.
* It stops reading when a space is encountered.
* Suitable for single-word strings.
