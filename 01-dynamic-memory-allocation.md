# Dynamic Memory Allocation

Dynamic Memory Allocation (DMA) is a process of allocating memory during program execution.

Unlike static memory allocation, memory is assigned at runtime according to program requirements.

## Why Dynamic Memory Allocation?

* Efficient memory utilization
* Memory can be allocated when needed
* Useful when data size is unknown

## Functions Used

C provides four functions for Dynamic Memory Allocation:

* malloc()
* calloc()
* realloc()
* free()

To use these functions:

```c
#include <stdlib.h>
```

## Memory Areas

```text
Stack   → Local Variables
Heap    → Dynamic Memory Allocation
Code    → Program Instructions
Data    → Global Variables
```
