# `signed char`

> **Range:** `SCHAR_MIN` / `SCHAR_MAX`.  
> **Format specifier:** `%c` or `%hhi`.  
> **Minimum size:** 8 bits.

Declaration:

```c
signed char a = 'A';
```

Range:

```c
#include <stdio.h>
#include <limits.h>

int main(void) {
    printf("SCHAR_MIN: %d, SCHAR_MAX: %d", SCHAR_MIN, SCHAR_MAX);
    return 0;
}

// Sample output:
// SCHAR_MIN: -128, SCHAR_MAX: 127
```