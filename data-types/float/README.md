# `float`

> **Range:** `FLT_MIN` / `FLT_MAX`.
> **Format specifier:** `%f`, `%g`, `%e`, `%a`, `%F`, `%G`, `%E`, `%A`.  
> **Minimum size:** 32 bits.

Declaration:

```c
float x = 10.25;
```

Size and range:

```c
#include <stdio.h>
#include <float.h>

int main()
{
    size_t float_size = sizeof(float);
    printf("Size of float: %zu bytes\n", float_size);
    printf("FLT_MIN: %e, FLT_MAX: %e\n", FLT_MIN, FLT_MAX);
    return 0;
}

// Sample output:
// Size of float: 4 bytes
// FLT_MIN: 1.175494e-38, FLT_MAX: 3.402823e+38
```