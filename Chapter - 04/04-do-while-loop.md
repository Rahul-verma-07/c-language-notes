# Do-While Loop

A do-while loop executes the code first and checks the condition afterward.

This loop executes at least one time.

## Syntax

```c
do {
    // code
} while(condition);
```

## Example

```c
#include <stdio.h>

int main() {

    int i = 0;

    do {
        printf("The value of i is %d\n", i);
        i++;
    }
    while(i <= 4);

    return 0;
}
```

## Key Difference

| While Loop             | Do-While Loop      |
| ---------------------- | ------------------ |
| Checks condition first | Executes first     |
| May run zero times     | Runs at least once |
