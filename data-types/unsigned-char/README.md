# `unsigned char`

> **Range:** `0` / `UCHAR_MAX`.  
> **Format specifier:** `%c` or `%hhu`.  
> **Minimum size:** 8 bits.

Declaration:

```c
unsigned char b = 'B';
```

Range:

```c
#include <stdio.h>
#include <limits.h>

int main(void) {
    printf("UCHAR_MAX: %d\n", UCHAR_MAX);
    return 0;
}

// Sample output:
// UCHAR_MAX: 255
```