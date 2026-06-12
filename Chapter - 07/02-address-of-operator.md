# Address Of Operator (&)

The address-of operator (`&`) is used to obtain the memory address of a variable.

## Syntax

```c
&variable_name
```

## Example

```c
#include <stdio.h>

int main() {

    int a = 10;

    printf("%p", &a);

    return 0;
}
```

## Output

Displays the memory address of `a`.
