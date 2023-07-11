# `unsigned long long`

> **Range:** `0` / `ULLONG_MAX`.  
> **Format specifier:** `%llu`.  
> **Minimum size:** 64 bits.

Declaration:

```c
unsigned long long x = 1000000000000000;
unsigned long long int y = 2000000000000000;
```

Range:

```c
#include <stdio.h>
#include <limits.h>

int main(void) {
    printf("ULLONG_MAX: %llu", ULLONG_MAX);
    return 0;
}

// Sample output:
// ULLONG_MAX: 18446744073709551615
```