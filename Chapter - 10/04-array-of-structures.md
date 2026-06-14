# Array of Structures

An array of structures stores multiple structure variables.

## Example

```c
#include <stdio.h>

struct employee {
    char name[30];
    int age;
};

int main() {

    struct employee emp[100];

    return 0;
}
```

## Usage

Useful when managing many records such as:

* Employees
* Students
* Products
