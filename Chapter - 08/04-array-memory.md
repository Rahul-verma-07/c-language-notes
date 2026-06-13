# Arrays in Memory

Array elements are stored in contiguous memory locations.

## Example

```c
int arr[3] = {1, 2, 3};
```

## Memory Usage

For integers:

```text
1 Integer = 4 Bytes
3 Integers = 12 Bytes
```

## Memory Representation

```text
Index    Value
-----    -----
0          1
1          2
2          3
```

### Benefits

* Fast access using indexes.
* Efficient memory utilization.
