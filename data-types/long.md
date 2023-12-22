# `long`

> **Range:** `LONG_MIN` / `LONG_MAX`.  
> **Format specifiers:** `%li` or `%ld`.  
> **Minimum size:** 32 bits.

### Declaration

```c
long w;
long int x;
signed long y;
signed long int z;
```

### Range

```c
#include <stdio.h>
#include <limits.h>

int main()
{
    printf("LONG_MIN: %li, LONG_MAX: %ld\n", LONG_MIN, LONG_MAX);
    return 0;
}

// Sample output:
// LONG_MIN: -9223372036854775808, LONG_MAX: 9223372036854775807
```