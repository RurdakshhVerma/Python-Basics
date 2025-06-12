# Python Basics Study Notes

This repository contains my study notes and key concepts from learning the basics of Python. The topics covered include fundamental concepts, programming constructs, and important features of the Python language.

## Table of Contents
- [Introduction to Python](#introduction-to-python)
- [Predefined Keywords](#predefined-keywords)
- [Mutability & Immutability](#mutability--immutability)
- [Operators](#operators)
- [Type Casting](#type-casting)
- [Conditionals](#conditionals)
- [Loops](#loops)

---

## Introduction to Python

Python is a high-level, versatile, and easy-to-read programming language. It is widely used for web development, data analysis, automation, artificial intelligence, and more. Python’s simple syntax and readability make it a great choice for beginners.

---

## Predefined Keywords

**Keywords** are reserved words in Python that have special meanings. They cannot be used as variable names. Examples include `if`, `else`, `for`, `while`, `def`, `class`, etc.

To get a list of all keywords in Python:
```python
import keyword
print(keyword.kwlist)
```

---

## Mutability & Immutability

- **Mutable objects** can be changed after creation (e.g., lists, dictionaries, sets).
- **Immutable objects** cannot be changed after creation (e.g., strings, tuples, integers).

Example:
```python
# Mutable
my_list = [1, 2, 3]
my_list[0] = 10  # This works

# Immutable
my_tuple = (1, 2, 3)
# my_tuple[0] = 10  # This will give an error
```

---

## Operators

Python supports several types of operators:
- **Arithmetic Operators:** `+`, `-`, `*`, `/`, `//`, `%`, `**`
- **Comparison Operators:** `==`, `!=`, `>`, `<`, `>=`, `<=`
- **Logical Operators:** `and`, `or`, `not`
- **Assignment Operators:** `=`, `+=`, `-=`, etc.

---

## Type Casting

Type casting is converting one data type to another. Common functions:
- `int()`
- `float()`
- `str()`
- `bool()`

Example:
```python
a = "5"
b = int(a)  # b is now an integer 5
```

---

## Conditionals

Conditionals allow your code to make decisions based on conditions.

Example:
```python
x = 10
if x > 5:
    print("x is greater than 5")
elif x == 5:
    print("x is 5")
else:
    print("x is less than 5")
```

---

## Loops

Loops are used for repeated execution of a block of code.
- **For loop:** Iterates over a sequence.
- **While loop:** Repeats as long as a condition is true.

Examples:
```python
# For loop
for i in range(5):
    print(i)

# While loop
count = 0
while count < 5:
    print(count)
    count += 1
```

---

## License

This repository is for educational purposes.
