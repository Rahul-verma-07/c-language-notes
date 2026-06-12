# Value At Address Operator (*)

The `*` operator is used to access the value stored at a memory address.

It is also known as the **Dereference Operator**.

## Example

```c
#include <stdio.h>

int main() {

    int a = 5;
    int *ptr = &a;

    printf("%d", *ptr);

    return 0;
}
```

## Output

```text
5
```

### Important

```c
*ptr
```

means:

```text
Value stored at the address contained in ptr.
```
