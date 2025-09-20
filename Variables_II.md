
[⟵ Printing to Console II](Printing_II.md) __________ [Table of Contents](README.mb) __________ [Next ⟶](next.md)

# Variables II: Advanced Information

## Data Types

In [Variables I](Variables_I.md) we learned that variables are used to store values. Now
 we are going to go indepth in this topic. The 4 datatypes shown below are called **_Primitive Data Types_**.

| Data Type | Data Type Name | Explanation | Value | Example |
| --------- | -------------- | ----------- | ----- | ------- |
| `int` | Integer |Integer numbers, numbers without the decimal point. | `23, 47, 59` | `int age = 18;` |
| `float` | Floating Point Number | Decimal numbers like 𝜋, they contain a decimal point. The precision is about 6 decimal places. They can also be written in scientific form. | `3.141594` | `float height = 0.165531;`, `float scientificForm = 8.99e-10;` |
| `double` | Floating Point Number | Decimal numbers like 𝜋, they contain a decimal point. They are similar to `float` but have more precision than `float`s. The precision is 15 decimal places. Like `float`s, `doubles` can be written in scientific notation. | `1.987654218362831`, `1.45e12` | `double picometer = 0.0000000000001;`<br>`double picometer = 1.0e-12;` |
| `char` | Character | They contains either a single letter (UPPERCASE or lowercase), a number<br> or, a symbol. When writing chars, they must be enclosed in single quotes ' '. | `'a'`, `'B'`, `'5'`, `'#'` | `char grade = 'A';`<br>`char num = '5';`<br>`char symbol = '#';` |

When looking at the table we can see that there are no booleans and strings. It will come later.<br>

## Identifiers

When we create variables, we give it a name, same like in math. The names of the variables are used to identify it and it's use case.
A number that has a value that relates to age would be called age. Vice versa, when the variable stores an age, we name it age so we
can recognized it. These variable names are called **_Identifiers_**.

Let's see a few examples of Good Identifiers:
```C
int heightInCm = 170;
char letterGrade = 'B';
char heading1 = '#';
double winningPercentage = 127.572;
```
1. We can understand the heightInCm means that the value is the height of a person.
2. letterGrade explains that it is a letter grade with a value of B
3. heading1 is a char with value #. (Heading 1 in Markdown is represented with #)
4. winningPercentage tells that the chance of winning is %127.572.

Now the code below shows Bad Identifiers:
```C
int value1 = 27;
float value2 = 27.452;
double value3 = 39.9362020736;
char value4 = 'Z';
```

With those values about, we can not tell what the purpose of these variables are. What is value1 for? age? We won't know since it is not self-explanatory.
