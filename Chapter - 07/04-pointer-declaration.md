# Declaring a Pointer

A pointer is declared using the `*` symbol.

## Syntax

```c
data_type *pointer_name;
```

## Example

```c
int *ptr;
```

Pointer to an integer.

```c
char *ptr;
```

Pointer to a character.

## Initialization

```c
int a = 10;
int *ptr = &a;
```

Here:

* `a` stores the value.
* `ptr` stores the address of `a`.
