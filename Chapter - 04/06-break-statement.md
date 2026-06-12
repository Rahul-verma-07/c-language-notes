# Break Statement

The break statement is used to immediately terminate a loop.

## Example

```c
#include <stdio.h>

int main() {

    for(int i = 0; i <= 5; i++) {

        if(i == 3) {
            break;
        }

        printf("%d\n", i);
    }

    return 0;
}
```

## Output

```text
0
1
2
```

The loop stops when `i` becomes 3.
