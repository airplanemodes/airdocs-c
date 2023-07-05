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

Size and range:

```c
#include <stdio.h>
#include <limits.h>

int main()
{
    size_t int_size = sizeof(int);
    printf("Size of int: %zu bytes\n", int_size);
    printf("INT_MIN: %d, INT_MAX: %d\n", INT_MIN, INT_MAX);
    return 0;
}

// Sample output:
// Size of int: 4 bytes
// INT_MIN: -2147483648, INT_MAX: 2147483647
```