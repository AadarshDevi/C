
# Basic C Program Structure

This is the standard default C program:
```c
#include <stdio.h>
int main()
{
  return 0;
}
```

This `#include <stdio.h>` is used for printing values to the console and also getting user input.<br>
The `int main()` is the starting point for the C program. When a C program is converted into an executable,
it will first check for this. Without this, the exe file cannot fun.<br>

# Printing to Console I

To print anything in C, we use the same line of code: `printf("text")`. below we are printing "Hello World, I am coding in C!".

```c
printf("Hello World, I am coding in C!");
```
