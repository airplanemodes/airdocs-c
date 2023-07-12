# `break`

Terminates the current [`for`](/statements/for.md), [`while`](/statements/while.md) or [`switch`](/statements/switch.md) execution.

### Examples

Breaking the [`for`](/statements/for.md) loop:

```c
#include <stdio.h>

int main()
{
    for (int i = 0; i < 10; i++) {
        if (i == 4) { break; }
        printf("%d\n", i);
    }
    return 0;
}

// Sample output:
// 0
// 1
// 2
// 3
```