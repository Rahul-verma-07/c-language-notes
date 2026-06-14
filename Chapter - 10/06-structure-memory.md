# Structure Memory

Structure members are stored in memory.

## Example

```c
struct employee {

    char name[30];
    int age;
    float salary;
};
```

Memory is allocated for each member of the structure.

## Important

The total memory consumed depends on:

* Data types used
* Structure padding
* Alignment rules

Structures occupy contiguous memory blocks.
