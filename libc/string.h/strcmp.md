# `strcmp()`

> Returns `int`.

Compares values of **s1** and **s2**.

The comparsion is done using [`unsigned char`](/data-types/unsigned-char/), character by character.

### Syntax

```c
strcmp(char *s1, char *s2);
```

### Examples

Returns `0` in case of both strings are equal:

```c
#include <stdio.h>
#include <string.h>

int main(void)
{
    int equal = strcmp("aaa", "aaa");
    printf("%d\n", equal);
    return 0;
}

// Sample output:
// 0
```