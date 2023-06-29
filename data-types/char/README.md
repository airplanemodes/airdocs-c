# `char`

> **Range:** `CHAR_MIN` / `CHAR_MAX`.  
> **Format specifier:** `%c`.  
> **Minimum size:** 8 bits.

Declaration:

```c
char letter = 'a'; // single quotation marks are required!
```

Range:

```c
#include <stdio.h>
#include <limits.h>

int main()
{
    printf("The range is from %d to %d\n", CHAR_MIN, CHAR_MAX);
    return 0;
}

// Sample output:
// The range is from -128 to 127
```