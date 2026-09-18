# C Basics

## 1. Data Types

Data Type | Description

`int` Stores integer values.

`float` Stores single-precision floating-point values.

`char` Stores a single character.                     |

`void` Represents the absence of a value.

## 2. Format Specifiers

`%d` | Displays a signed decimal integer.

`%u` | Displays an unsigned integer.

`%f` | Displays a floating-point value.

`%e` | Displays a floating-point value in exponential notation.

`%c` | Displays a character.

`%s` | Displays a string.

`%ld`| Displays a long integer.

## 3. Input/Output Functions

### scanf() is used to take formatted input from the user.

### printf() is used to display formatted output.

### getchar() reads a single character from the input.

### putchar() displays a single character.

### fgets() is used to read a line of text, including spaces.

### puts()  displays a string followed by a new line.

## 4. Escape Sequences

| `\n`| New line
| `\t`| Horizontal tab
| `\\`| Backslash
| `\'`| Single quotation mark

## 5. Precision

Precision controls how many digits are displayed after the decimal point for floating-point output.

For example:

```c
printf("%.2f", value);
```

displays the value with 2 digits after the decimal point.
