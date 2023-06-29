# `unsigned`

> **Range:** `0` / `UINT_MAX`.  
> **Format specifier:** `%u`.  
> **Minimum size:** 16 bits.

Declaration:

```c
unsigned x = 10;
unsigned int y = 20;
```

Range:

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