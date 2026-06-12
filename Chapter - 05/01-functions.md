# Functions

A function is a block of code that performs a specific task.

Functions help break large programs into smaller and reusable parts.

## Benefits of Functions

* Reusability
* Better code organization
* Easier debugging
* Improved readability

## Example

```c
#include <stdio.h>

int sum(int x, int y) {
    return x + y;
}

int main() {
    printf("%d", sum(5, 10));
    return 0;
}
```
