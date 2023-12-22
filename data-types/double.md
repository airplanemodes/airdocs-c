# `double`

> **Range:** `DBL_MIN` / `DBL_MAX`.  
> **Format specifiers:** `%lf`, `%lg`, `%le`, `%la`, `%lF`, `%lG`, `%lE`, `%lA`.  
> **Minimum size:** 64 bits.

### Declaration

```c
double x;
```

### Size and range

```c
#include <stdio.h>
#include <float.h>

int main()
{
    size_t double_size = sizeof(double);
    printf("Size of double: %zu bytes\n", double_size);
    printf("DBL_MIN: %e, DBL_MAX: %e\n", DBL_MIN, DBL_MAX);
    return 0;
}

// Sample output:
// Size of double: 8 bytes
// DBL_MIN: 2.225074e-308, DBL_MAX: 1.797693e+308
```