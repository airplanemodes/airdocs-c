# `short`

> **Range:** `SHRT_MIN` / `SHRT_MAX`.  
> **Format specifiers:** `%hi` or `%hd`.  
> **Minimum size:** 16 bits.

### Declaration

```c
short w;
short int x;
signed short y;
signed short int z;
```

### Range

```c
#include <stdio.h>
#include <limits.h>

int main()
{
    printf("SHRT_MIN: %d, SHRT_MAX: %d\n", SHRT_MIN, SHRT_MAX);
    return 0;
}

// Sample output:
// SHRT_MIN: -32768, SHRT_MAX: 32767
```