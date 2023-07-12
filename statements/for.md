# `for`

### Syntax

```c
for (initialization; condition expression; iteration expression) {
    statements;
}
```

### Examples

The endless `for` loop:

```c
for (;;) {
    printf("Infinity...");
}
```

`for` loop with the null statement:

```c
for (int i = 0; i < 10; i++) {
    ;
}
```