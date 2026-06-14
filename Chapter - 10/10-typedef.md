# Typedef Keyword

The `typedef` keyword is used to create an alias for a data type.

## Example

```c
typedef struct vec {

    int i;
    int j;

} vec;
```

Now instead of writing:

```c
struct vec v1;
```

you can write:

```c
vec v1;
```

## Advantages

* Reduces code length
* Improves readability
* Simplifies structure declarations
