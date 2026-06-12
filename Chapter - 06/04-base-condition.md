# Base Condition

A base condition is the condition that stops recursive calls.

Without a base condition, recursion will continue indefinitely and eventually cause a stack overflow error.

## Example

```c
int factorial(int n) {

    if(n == 1)
        return 1;

    return n * factorial(n - 1);
}
```

Here:

```c
if(n == 1)
```

is the base condition.

## Important Points

* Every recursive function must have a base condition.
* It prevents infinite recursion.
* It acts as the stopping point of recursion.

### Note

If a recursive function does not contain a base condition, the program may crash due to excessive memory usage.
