# `abs()`

> Return type: [`int`](/data-types/int/).  
> Standard: **ISO/IEC 9899:1999** (C99).

Computes the absolute value of **n**.

### Syntax

```c
abs(int n);
```

### Examples

```c
#include <stdio.h>
#include <stdlib.h>

int main()
{
    int n = -10;
    n = abs(n);
    printf("n is %d\n", n);
    return 0;
}

// Sample output:
// n is 10
```