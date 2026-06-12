# Switch Case

The switch statement is used when there are multiple possible choices.

## Example

```c
#include <stdio.h>

int main() {

    int choice;

    scanf("%d", &choice);

    switch(choice) {

        case 1:
            printf("Hello World");
            break;

        case 2:
            printf("Hello");
            break;

        default:
            printf("Invalid Choice");
    }

    return 0;
}
```

## Important Notes

* Cases can be written in any order.
* Character values can be used as cases.
* The `break` statement exits the switch block.
* The `default` block executes when no case matches.
