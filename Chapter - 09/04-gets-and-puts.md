# gets() and puts()

## gets()

Used to receive a multi-word string from the user.

### Example

```c
#include <stdio.h>

int main() {

    char str[30];

    gets(str);

    printf("%s", str);

    return 0;
}
```

## puts()

Used to display a string.

### Example

```c
#include <stdio.h>

int main() {

    char str[30];

    gets(str);

    puts(str);

    return 0;
}
```

## Advantage

Unlike `scanf()`, `gets()` can accept spaces.
