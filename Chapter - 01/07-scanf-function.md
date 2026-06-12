# scanf() Function

The `scanf()` function is used to take input from the user.

## Syntax

```c
scanf("format_specifier", &variable);
```

## Example

```c
#include <stdio.h>

int main() {
    int a;

    printf("Enter a number: ");
    scanf("%d", &a);

    printf("You entered: %d", a);

    return 0;
}
```

## Important

The `&` operator is used to provide the address of the variable.
