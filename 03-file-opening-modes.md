# File Opening Modes

Files are opened using the `fopen()` function.

## Syntax

```c
FILE *ptr;

ptr = fopen("filename.txt", "mode");
```

## Common Modes

| Mode | Description                |
| ---- | -------------------------- |
| r    | Open for reading           |
| w    | Open for writing           |
| a    | Open for appending         |
| r+   | Read and write             |
| w+   | Read and write (overwrite) |
| a+   | Read and append            |

## Example

```c
FILE *ptr;

ptr = fopen("sample.txt", "r");
```
