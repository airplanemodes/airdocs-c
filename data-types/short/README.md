# `short`

> **Range:** `SHRT_MIN` / `SHRT_MAX`.  
> **Format specifier:** `%hi` or `%hd`.  
> **Minimum size:** 16 bits.

Declaration:

```c
short w = 10;
short int x = 20;
signed short y = 30;
signed short int z = 40;
```

Range:

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