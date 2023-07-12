# `continue`

Terminates the current [`for`](/statements/for.md) or [`while`](/statements/while.md) iteration and continues with the next iteration.

### Examples

Pass one iteration of the [`for`](/statements/for.md) loop:

```c
#include <stdio.h>

int main()
{
    for (int i = 0; i < 5; i++) {
        if (i == 2) { continue; }
        printf("%d\n", i);
    }
    return 0;
}

// Sample output:
// 0
// 1
// 3
// 4
```