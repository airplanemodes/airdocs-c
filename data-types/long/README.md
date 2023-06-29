# `long`

> **Range:** `LONG_MIN` / `LONG_MAX`.  
> **Format specifier:** `%li` or `%ld`.  
> **Minimum size:** 32 bits.

Declaration:

```c
long x = 1000000000;
long int y = 1200000000;
signed long z = -1500000000;
signed long int z = -1000000000;
```

Range:

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