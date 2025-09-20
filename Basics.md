
[Table of Contents](README.md) __________ [Printing to Output →](Printing.md)

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

# Comments

<p>
  We sometimes need to write text that is not code. During this time, we use comments. Many
  times, it is used to explain some code that is hard to understand or to document the code
  for the people who are going to inherit it.
</p>
<p>Comments are text that are ignored by the C compiler.</p>

```C
  // this is a single line comment
  /*
      this is a
      multi-line
      comment
  */
```

# Variables I

<p>
  When we create our program, we have values that need to be stored but also change sometimes or constantly.
  These values are stored in containers called variables. so when we have to store a value like age, we can
  store it in a variable.
  - Variables in C work the same way variables in math work.
</p>

<p>There are many times of values and they are listed below:</p>

```
int number = 215;
float num2 = 107.75;
char let = 'A';
char let2 = 'D';
```

Here the values represent different types of variables. These types are called Data Types.<br>
from the examples there is a few information<br>

`int, float, char` are called Data Types and `number, num2, let, let2` are called identifiers, they tell use what the variable is created for.
