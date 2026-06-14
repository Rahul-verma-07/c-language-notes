# Closing Files

After performing file operations, files should be closed.

## Syntax

```c
fclose(file_pointer);
```

## Example

```c
FILE *ptr;

ptr = fopen("sample.txt", "r");

fclose(ptr);
```

## Benefits

* Saves memory
* Prevents data corruption
* Releases system resources
