# Accessing Array Elements

Array elements are accessed using their index number.

## Example

```c
#include <stdio.h>

int main() {

    int arr[3];

    printf("Enter three numbers:\n");

    scanf("%d", &arr[0]);
    scanf("%d", &arr[1]);
    scanf("%d", &arr[2]);

    printf("%d %d", arr[0], arr[2]);

    return 0;
}
```

## Important

```text
First Element  → arr[0]
Second Element → arr[1]
Third Element  → arr[2]
```
