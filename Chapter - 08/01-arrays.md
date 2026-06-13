# Arrays

An array is a collection of similar data types stored in contiguous memory locations.

Arrays allow a single variable to store multiple values.

## Syntax

```c
data_type array_name[size];
```

## Example

```c
#include <stdio.h>

int main() {

    int arr[5];

    arr[0] = 1;
    arr[1] = 2;

    printf("%d %d", arr[0], arr[1]);

    return 0;
}
```

## Features

* Stores multiple values of the same type.
* Elements are stored sequentially.
* Indexing starts from `0`.
