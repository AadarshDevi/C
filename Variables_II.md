
[⟵ Printing to Console II](Printing_II.md) __________ [Table of Contents](README.mb) __________ [Next ⟶](next.md)

# Variables II: Advanced Information

## Data Types

In [Variables I](Variables_I.md) we learned that variables are used to store values. Now
 we are going to go indepth in this topic. The 4 datatypes shown below are called **___Primitive Data Types___**.

| Data Type | Data Type Name | Explanation | Value | Example |
| --------- | -------------- | ----------- | ----- | ------- |
| `int` | Integer |Integer numbers, numbers without the decimal point. | `23, 47, 59` | `int age = 18;` |
| `float` | Floating Point Number | Decimal numbers like 𝜋, they contain a decimal point. The precision is about 6 decimal places. They can also be written in scientific form. | `3.141594` | `float height = 0.165531;`, `float scientificForm = 8.99e-10;` |
| `double` | Floating Point Number | Decimal numbers like 𝜋, they contain a decimal point. They are similar to `float` but have more precision than `float`s. The precision is 15 decimal places. Like `float`s, `doubles` can be written in scientific notation. | `1.987654218362831`, `1.45e12` | `double picometer = 0.0000000000001;`<br>`double picometer = 1.0e-12;` |
| `char` | Character | They contains either a single letter (UPPERCASE or lowercase), a number<br> or, a symbol. When writing chars, they must be enclosed in single quotes ' '. | `'a'`, `'B'`, `'5'`, `'#'` | `char grade = 'A';`<br>`char num = '5';`<br>`char symbol = '#';` |

When looking at the table we can see that there are no booleans and strings. It will come later.

## Identifiers
