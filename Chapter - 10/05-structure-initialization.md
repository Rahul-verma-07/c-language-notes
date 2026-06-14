# Structure Initialization

Structures can be initialized during declaration.

## Example

```c
#include <stdio.h>

struct employee {
    char name[30];
    int age;
    float salary;
};

int main() {

    struct employee e1 = {
        "Rahul",
        21,
        50000.0
    };

    printf("%s %d %.2f",
           e1.name,
           e1.age,
           e1.salary);

    return 0;
}
```
