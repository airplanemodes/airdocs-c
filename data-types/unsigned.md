# `unsigned`

> **Range:** `0` / `UINT_MAX`.  
> **Format specifier:** `%u`.  
> **Minimum size:** 16 bits.

### Declaration

```c
unsigned x;
unsigned int y;
```

### Range

```c
#include <stdio.h>
#include <limits.h>

int main()
{
    printf("UINT_MAX: %u\n", UINT_MAX);
    return 0;
}

// Sample output:
// UINT_MAX: 4294967295
```