# Passing Arrays to Functions

Arrays can be passed directly to functions.

## Example

```c
#include <stdio.h>

void printArray(int a[], int n) {

    for(int i = 0; i < n; i++) {
        printf("%d ", a[i]);
    }

    printf("\n");
}

int main() {

    int arr[] = {1, 2, 3, 4, 5};

    printArray(arr, 5);

    return 0;
}
```

## Advantages

* Reduces code duplication.
* Makes programs modular.
* Easier maintenance.
