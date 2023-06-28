# `int`

> **Range:** `INT_MIN` / `INT_MAX`.  
> **Format specifier:** `%i` or `%d`.  
> **Minimum size:** 16 bits.

Declaration:

```c
int x = 10;
signed y = 20;
signed int z = 30;
```

Range:

```c
#include <stdio.h>
#include <limits.h>

int main()
{
    printf("INT_MIN: %d, INT_MAX: %d\n", INT_MIN, INT_MAX);
    return 0;
}

// Sample output:
// INT_MIN: -2147483648, INT_MAX: 2147483647
```