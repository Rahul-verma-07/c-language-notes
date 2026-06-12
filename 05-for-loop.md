# For Loop

The for loop is used when the number of iterations is known.

## Syntax

```c
for(initialization; condition; increment)
{
    // code
}
```

## Example

```c
#include <stdio.h>

int main() {

    for(int i = 0; i <= 4; i++) {
        printf("Hello World! %d\n", i);
    }

    return 0;
}
```

## Components

### Initialization

```c
int i = 0;
```

### Condition

```c
i <= 4
```

### Increment

```c
i++
```
