# Taking Structure Input

Structure members can receive input from the user.

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

    printf("Enter Name: ");
    scanf("%s", e1.name);

    printf("Enter Age: ");
    scanf("%d", &e1.age);

    printf("Enter Salary: ");
    scanf("%f", &e1.salary);

    printf("%s %d %.2f",
           e1.name,
           e1.age,
           e1.salary);

    return 0;
}
```
