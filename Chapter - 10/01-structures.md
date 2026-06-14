# Structures

A structure is a user-defined data type that allows storing different types of data under a single name.

## Why Structures?

Structures help combine related data into one unit.

## Example

```c
#include <stdio.h>

struct employee {
    char name[30];
    int age;
    float salary;
};

int main() {

    struct employee e1;

    return 0;
}
```

## Structure Example

```text
Employee
├── Name
├── Age
└── Salary
```

Structures store dissimilar data types together.
