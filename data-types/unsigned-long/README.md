# `unsigned long`

> **Range:** `0` / `ULONG_MAX`.  
> **Format specifier:** `%lu`.  
> **Minimum size:** 32 bits.

Declaration:

```c
unsigned long x = 1000000000;
unsigned long int y = 2000000000;
```

Range:

```c
#include <stdio.h>
#include <limits.h>

int main(void) {
    printf("ULONG_MAX: %lu", ULONG_MAX);
    return 0;
}

// Sample output:
// ULONG_MAX: 18446744073709551615
```