# `unsigned short`

> **Range:** `0` / `USHRT_MAX`.  
> **Format specifier:** `%hu`.  
> **Minimum size:** 16 bits.

Declaration:

```c
unsigned short x = 10;
unsigned short int y = 20;
```

Range:

```c
#include <stdio.h>
#include <limits.h>

int main()
{
    printf("USHRT_MAX: %d\n", USHRT_MAX); // %d because the value stored as int
    return 0;
}

// Sample output:
// USHRT_MAX: 65535
```