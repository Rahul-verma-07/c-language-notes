# Increment and Decrement Operators

These operators are used to increase or decrease the value of a variable.

## Increment Operator

```c
i++;
```

Increases the value of `i` by 1.

## Decrement Operator

```c
i--;
```

Decreases the value of `i` by 1.

## Post Increment

```c
i++;
```

* Prints first
* Then increments

## Pre Increment

```c
++i;
```

* Increments first
* Then prints

## Example

```c
#include <stdio.h>

int main() {

    int i = 5;

    printf("%d\n", i++);
    printf("%d\n", ++i);

    return 0;
}
```
