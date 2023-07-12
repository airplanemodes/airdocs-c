# `pow()`

> Return type: [`double`](/data-types/double/).  
> Standard: **ISO/IEC 9899:2011** (C11).

### Syntax

```c
pow(double x, double y);
```

### Examples

```c
#include <stdio.h>
#include <math.h>

int main(void)
{
    double x = 5;
    double y = 2;
    double z = pow(x, y);
    printf("z is %f\n", z);
    return 0;
}

// Sample output:
// z is 25.000000
```