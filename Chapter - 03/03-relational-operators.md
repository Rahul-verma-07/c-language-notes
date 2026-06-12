# Relational Operators

Relational operators compare two values and return either true or false.

## Operators

| Operator | Meaning                  |
| -------- | ------------------------ |
| ==       | Equal to                 |
| !=       | Not equal to             |
| >        | Greater than             |
| <        | Less than                |
| >=       | Greater than or equal to |
| <=       | Less than or equal to    |

## Example

```c
#include <stdio.h>

int main() {
    int a = 10;
    int b = 20;

    printf("%d", a < b);

    return 0;
}
```

## Output

```text
1
```

### Note

In C language:

* Non-zero value = True
* Zero value = False
