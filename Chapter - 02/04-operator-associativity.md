# Operator Associativity

Associativity determines the order in which operators of the same precedence are evaluated.

Most arithmetic operators are evaluated from left to right.

## Example

```c
#include <stdio.h>

int main() {
    int result = 20 / 5 * 2;

    printf("%d", result);

    return 0;
}
```

## Evaluation

```text
20 / 5 = 4
4 * 2  = 8
```

## Output

```text
8
```

### Important

Expression:

```c
x * y / z
```

is evaluated as:

```c
(x * y) / z
```

because `*` and `/` have the same precedence and are evaluated from left to right.