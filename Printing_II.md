
[⟵ Variables I](Variables_I.md) __________ [Table of Contents](README.mb) __________ [Variables II ⟶](Variables_II.md)

# Printing to Console II: Output with Variables

In [Printing to Console](Printing_I.md) we found a way to print to the console.<br>
So now, we have a variable first name inital and age, we need to print it to the console.
<br>
<br>
We know that first name initial is a `char` and age is an `int` so print these values, we<br>
We are going to use Format Specifiers. Format Specifiers are special characters used to print our<br>
values to the console. <br><br>
Below are some variables and their Format Specifiers.

| Data Type | Format Specifiers |
| --------- | ----------------- |
| `int` | `printf("number: %d", num);` |
| `float` | `printf("precise number: %f", pi);` |
| `double` | `printf("really precise number: %lf", pi);` |
| `char` | `printf("letter: %c", letter);` |


```C
    printf("\n\nInteger Number: %d", number);
    printf("\nFloating Point Number: %f", num2);
    printf("\nCharacter: %c", let);
```
