# Conditional Instructions

Conditional instructions allow a program to make decisions based on conditions.

## if-else Statement

```c
#include <stdio.h>

int main() {
    int age = 15;

    if(age > 18) {
        printf("Adult");
    }
    else {
        printf("Minor");
    }

    return 0;
}
```

## Output

```text
Minor
```

### Uses

* Decision making
* Checking conditions
* Controlling program flow
