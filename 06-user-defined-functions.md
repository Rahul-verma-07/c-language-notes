# User Defined Functions

User defined functions are created by programmers to perform specific tasks.

## Example

```c
#include <stdio.h>

// Funtion defined by the user
int square(int n) {
    return n * n;
}

int main() {

    printf("%d", square(5)); // Function called by the user

    return 0;
}
```

## Output

```text
25
```
