# `floor()`

> Return type: [`double`](/data-types/double/).  
> Standard: **ISO/IEC 9899:2011** (C11).

### Syntax

```c
floor(double x);
```

### Examples

```c
#include <stdio.h>
#include <math.h>

int main(void)
{
    double x = 2.95;
    x = floor(x);
    printf("x is %f\n", x);
    return 0;
}

// Sample output:
// x is 2.000000
```