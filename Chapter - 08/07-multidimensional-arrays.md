# Multidimensional Arrays

A multidimensional array is an array containing other arrays.

Common types:

* 2D Array
* 3D Array
* nD Array

## 2D Array Example

```c
#include <stdio.h>

int main() {

    int arr[3][2] = {
        {1, 2},
        {3, 4},
        {5, 6}
    };

    for(int i = 0; i < 3; i++) {

        for(int j = 0; j < 2; j++) {

            printf("%d ", arr[i][j]);
        }

        printf("\n");
    }

    return 0;
}
```

## Output

```text
1 2
3 4
5 6
```

## Applications

* Matrices
* Tables
* Image Processing
* Scientific Computation
