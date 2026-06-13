# Array Initialization

Arrays can be initialized at the time of declaration.

## Syntax

```c
int arr[3] = {10, 20, 30};
```

## Example

```c
#include <stdio.h>

int main() {

    int arr[3] = {10, 20, 30};

    for(int i = 0; i < 3; i++) {
        printf("%d\n", arr[i]);
    }

    return 0;
}
```

## Output

```text
10
20
30
```
