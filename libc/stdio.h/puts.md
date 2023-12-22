# `puts()`

> Return type: [`int`](/data-types/int/) on success or `EOF` on error.  
> Standard: **ISO/IEC 9899:1990** (C90).

Output a line to [`stdout`](/libc/stdio.h/stdout.md).

?> If **str** is `NULL` the output will be `(null)`.

### Syntax

```c
puts(const char *str);
```

### Examples

```c
#include <stdio.h>

int main()
{
    char str[20] = "Once upon a time...";
    puts(str);
    return 0;
}

// Sample output:
// Once upon a time...
```