# `long long`

> **Range:** `LLONG_MIN` / `LLONG_MAX`.  
> **Format specifiers:** `%lli` or `%lld`.  
> **Minimum size:** 64 bits.

### Declaration

```c
long long w;
long long int x;
signed long long y;
signed long long int z;
```

### Range

```c
#include <stdio.h>
#include <limits.h>

int main()
{
    printf("LLONG_MIN: %lli, LLONG_MAX: %lld\n", LLONG_MIN, LLONG_MAX);
    return 0;
}

// Sample output:
// LONG_MIN: -9223372036854775808, LONG_MAX: 9223372036854775807
```