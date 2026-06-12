# Recursive Functions

A recursive function is a function that calls itself.

## Structure

```c
return_type function_name(parameters) {

    if(base_condition)
        return value;

    return function_name(smaller_problem);
}
```

## Example

```c
int factorial(int n) {

    if(n == 1)
        return 1;

    return n * factorial(n - 1);
}
```

## Benefits

* Simple implementation of complex problems
* Useful for tree and graph algorithms
* Reduces code size

## Drawbacks

* Higher memory usage
* Can be slower than loops
* Risk of infinite recursion
