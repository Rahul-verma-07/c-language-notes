# Type Conversion

When different data types are used in an expression, C automatically converts them to a suitable type.

## Rules

```text
int + int     → int
int + float   → float
float + float → float
```

## Example

```c
#include <stdio.h>

int main() {
    int a = 5;
    float b = 2.5;

    printf("%f", a + b);

    return 0;
}
```

## Output

```text
7.500000
```
