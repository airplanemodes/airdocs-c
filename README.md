# `Introduction`

### The `main()` function

According to the C standard the `main` function should have a return type of [`int`](/data-types/int/).  
The return value from the `main` function is used to indicate the exit status of the program to the operating system or the invoking environment.

```c
int main(void)
{
    return 0; // exit status
}
```

The `main` function is available to access command-line arguments if defined as follows:

```c
int main(int argc, char *argv[])
{
    return 0;
}
```

`argc` represents the number of command-line arguments passed to the program, and `argv` represents an array of strings that holds the actual arguments.  
If a program being executed without additional arguments the value of `argc` will be `1` and the value of `argv[0]` will be the filename of a program itself.

Here is an example of a program saved as `first_program.c`:

```c
#include <stdio.h>

int main(int argc, char *argv[])
{
    printf("The number of arguments passed is: %d\n", argc);
    printf("The program name is: %s", argv[0]);
    return 0;
}
```

And this is what happens when the program is being compiled and executed:

```shell
cc first_program.c -o first_program
./first_program
# The number of arguments passed is: 1
# The program name is: ./first_program
```

### Header files

macOS location:

```
/Library/Developer/CommandLineTools/SDKs/MacOSX.sdk/usr/include
```

Linux location:

```
/usr/include
```