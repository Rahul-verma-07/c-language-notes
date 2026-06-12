# Call By Value

In call by value, a copy of the variable is passed to the function.

Any changes made inside the function do not affect the original variable.

## Example

```c
#include <stdio.h>

// Function defined to change value
void change(int a) {
    a = 77;
}

int main() {

    int b = 25;

    change(b); // Function called

    printf("%d", b);
    // No value will be changed

    return 0;
}
```

## Output

```text
25
```

### Why?

Because only a copy of `b` is passed to the function.

The original value remains unchanged.
