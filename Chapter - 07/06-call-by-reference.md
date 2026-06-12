# Call By Reference

In Call by Reference, the address of a variable is passed to a function.

Changes made inside the function affect the original variable.

## Example

```c
#include <stdio.h>

void change(int *x) {
    *x = 50;
}

int main() {

    int a = 10;

    change(&a);

    printf("%d", a);

    return 0;
}
```

## Output

```text
50
```

## Difference

| Call By Value            | Call By Reference      |
| ------------------------ | ---------------------- |
| Copy is passed           | Address is passed      |
| Original value unchanged | Original value changed |
