# Ternary Operator

The ternary operator is a shorthand form of if-else.

## Syntax

```c
condition ? expression1 : expression2;
```

## Example

```c
#include <stdio.h>

int main() {

    int a = 45;
    int b = 30;

    a >= b ? printf("TRUE") : printf("FALSE");

    return 0;
}
```

## Output

```text
TRUE
```
