# atoi()

> Return type: [`int`](/data-types/int/).  
> Standard: **ISO/IEC 9899:1990** (C90).

Convert ASCII string to [`int`](/data-types/int/).

### Syntax

```c
atoi(const char *str);
```

### Examples

```c
#include <stdio.h>
#include <stdlib.h>

int main()
{
    char str[4] = "255";
    printf("%d\n", atoi(str));
    return 0;
}

// Sample output:
// 255
```