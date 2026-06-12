# Continue Statement

The continue statement skips the current iteration and moves to the next iteration.

## Example

```c
#include <stdio.h>

int main() {

    for(int i = 0; i <= 5; i++) {

        if(i == 3) {
            continue;
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
4
5
```

## Difference Between Break and Continue

| Break                     | Continue                         |
| ------------------------- | -------------------------------- |
| Exits the loop completely | Skips only the current iteration |
| Terminates execution      | Continues execution              |

### Important Notes

* Variable names may not always indicate program behavior.
* `break` completely exits the loop.
* `continue` skips the current iteration only.
