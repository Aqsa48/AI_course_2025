# Python `if` and `else` Statements

## Introduction
Conditional statements in Python allow the program to make decisions and execute different blocks of code based on certain conditions.

## `if` Statement
The `if` statement executes a block of code if the condition evaluates to `True`.

```python
x = 10
if x > 5:
    print("x is greater than 5")
```

## `if-else` Statement
The `if-else` statement provides an alternative block of code when the condition is `False`.

```python
x = 3
if x > 5:
    print("x is greater than 5")
else:
    print("x is not greater than 5")
```

## `if-elif-else` Statement
The `elif` keyword allows multiple conditions to be checked in sequence.

```python
x = 10
if x < 5:
    print("x is less than 5")
elif x == 10:
    print("x is exactly 10")
else:
    print("x is greater than 5 but not 10")
```

## Nested `if` Statements
You can use an `if` statement inside another `if` statement.

```python
x = 20
if x > 10:
    print("x is greater than 10")
    if x > 15:
        print("x is also greater than 15")

```

---

## **Tasks for Students**
1. **Basic Task:** Write a program that checks if a given number is positive, negative, or zero.
2. **Intermediate Task:** Write a program that takes user input and determines whether it's a even or odd.
3. **Advanced Task:** Create a program that asks user to print:
   - `"Excellent"` if marks are above 80
   - `"Good"` if marks are between 60 and 80
   - `"Needs Improvement"` if marks are below 60
