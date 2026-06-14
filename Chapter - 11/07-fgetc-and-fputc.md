# fgetc() and fputc()

These functions are used for character-based file operations.

## fgetc()

Reads a single character from a file.

### Syntax

```c
fgetc(file_pointer);
```

### Example

```c
char ch;

ch = fgetc(ptr);
```

## fputc()

Writes a single character into a file.

### Syntax

```c
fputc(character, file_pointer);
```

### Example

```c
fputc('A', ptr);
```
