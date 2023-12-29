# `sprintf()`

> Return type: [`int`](/data-types/int/).  
> Standard: **ANSI X3.159-1989** (ANSI C89) and **ISO/IEC 9899:1999** (C99).

Writes the formatted output to the **str**.

Returns the number of characters printed, not including `\0`.

### Syntax

```c
// Until C99:
int sprintf(char * str, const char * format, ...);

// Since C99:
int sprintf(char * restrict str, const char * restrict format, ...);
```

### Examples

```c

```