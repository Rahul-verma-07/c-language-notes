# Logical Operators

Logical operators combine multiple conditions.

## Types

### AND (&&)

Returns true if both conditions are true.

```c
a > 5 && b > 5
```

### OR (||)

Returns true if at least one condition is true.

```c
a > 5 || b > 5
```

### NOT (!)

Reverses the result.

```c
!(a > 5)
```

## Example

```c
#include <stdio.h>

int main() {
    int age = 20;

    if(age > 18 && age < 60) {
        printf("Eligible");
    }

    return 0;
}
```
