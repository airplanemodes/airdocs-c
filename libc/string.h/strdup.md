# `strdup()`

### Syntax

```c
char * strdup(char * s1);
```

### Examples

```c
#include <stdio.h>
#include <string.h>

int main()
{
    char * str = "Some words.";
    char * new = strdup(str);
    printf("%s\n", new);
    return 0;
}

// Sample output:
// Some words.
```