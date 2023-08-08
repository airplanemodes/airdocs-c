# `long double`

> **Range:** `LDBL_MIN` / `LDBL_MAX`.  
> **Format specifiers:** `%Lf`, `%LF`, `%Lg`, `%LG`, `%Le`, `%LE`, `%La`, `%LA`.  
> **Minimum size:** 64 bits.

Declaration:

```c
long double x;
```

Size and range:

```c
#include <stdio.h>
#include <float.h>

int main()
{
    size_t ldouble_size = sizeof(long double);
    printf("Size of long double: %zu bytes\n", ldouble_size);
    printf("LDBL_MIN: %Le, LDBL_MAX: %Le\n", LDBL_MIN, LDBL_MAX);
    return 0;
}

// Sample output:
// Size of long double: 8 bytes
// LDBL_MIN: 2.225074e-308, LDBL_MAX: 1.797693e+308
```