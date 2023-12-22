# `unsigned long`

> **Range:** `0` / `ULONG_MAX`.  
> **Format specifier:** `%lu`.  
> **Minimum size:** 32 bits.

### Declaration

```c
unsigned long x;
unsigned long int y;
```

### Range

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