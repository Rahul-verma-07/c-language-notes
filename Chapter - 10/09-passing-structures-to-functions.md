# Passing Structures to Functions

Structures can be passed as arguments to functions.

## Example

```c
#include <stdio.h>

struct vec {
    int i;
    int j;
};

struct vec sumvec(struct vec v1,
                  struct vec v2) {

    struct vec v3 = {
        v1.i + v2.i,
        v1.j + v2.j
    };

    return v3;
}

int main() {

    struct vec v1 = {1, 2};
    struct vec v2 = {3, 4};

    struct vec v3 = sumvec(v1, v2);

    printf("%di + %dj",
           v3.i,
           v3.j);

    return 0;
}
```
