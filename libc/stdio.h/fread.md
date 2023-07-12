# `fread()`

> Return type: `size_t`.  
> Standard: **ISO/IEC 9899:1990** (C90).

### Syntax

Until C99:

```c
fread(void *ptr, size_t size, size_t count, FILE *stream);
```

Since C99:

```c
fread(void *restrict ptr, size_t size, size_t count, FILE *restrict stream);
```