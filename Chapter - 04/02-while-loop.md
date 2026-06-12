# While Loop

A while loop executes a block of code repeatedly as long as the given condition is true.

## Syntax

```c
while(condition) {
    // code
}
```

## Example

```c
#include <stdio.h>

int main() {
    int i = 0;

    while(i <= 4) {
        printf("Hello World!\n");
        i++;
    }

    return 0;
}
```

## Output

```text
Hello World!
Hello World!
Hello World!
Hello World!
Hello World!
```
