# Arrow Operator (->)

The arrow operator is used to access structure members through a pointer.

## Syntax

```c
pointer->member
```

## Example

```c
#include <stdio.h>

struct employee {
    char name[30];
    int age;
};

int main() {

    struct employee e1 = {
        "Rahul",
        21
    };

    struct employee *ptr = &e1;

    printf("%s", ptr->name);

    return 0;
}
```

## Equivalent Forms

```c
(*ptr).name
```

and

```c
ptr->name
```

Both produce the same result.
