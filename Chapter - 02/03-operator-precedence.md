# Operator Precedence

Operator precedence determines which operation is performed first in an expression.

## Order of Precedence

1. `*`, `/`, `%`
2. `+`, `-`
3. `==`, `!=`
4. `&&`
5. `||`

## Example

```c
#include <stdio.h>

int main() {
    int result = 2 + 3 * 4;

    printf("%d", result);

    return 0;
}
```

## Output

```text
14
```

Because multiplication is performed before addition.
