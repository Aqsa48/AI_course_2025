# Python `for` and `while` Loops

## Introduction
Loops in Python allow us to execute a block of code multiple times. Python provides two types of loops: `for` loops and `while` loops.

## `for` Loop
A `for` loop is used for iterating over a sequence (such as a list, tuple, string, or range).

```python
# Example: Iterating through a list
numbers = [1, 2, 3, 4, 5]
for num in numbers:
    print(num)
```

### Using `range()` in `for` Loops
The `range()` function generates a sequence of numbers.

```python
# Example: Printing numbers from 0 to 4
for i in range(5):
    print(i)
```

## `while` Loop
A `while` loop continues execution as long as the given condition remains `True`.

```python
# Example: Printing numbers using while loop
x = 0
while x < 5:
    print(x)
    x += 1
```

## Nested Loops
A loop inside another loop is called a nested loop.

```python
# Example: Nested loop for printing a pattern
for i in range(3):
    for j in range(3):
        print(f"({i}, {j})", end=" ")
    print()
```

## Loop Control Statements
Python provides loop control statements like `break`, `continue`, and `pass`.

### `break` Statement
Exits the loop when a condition is met.

```python
for num in range(10):
    if num == 5:
        break  # Stops the loop when num is 5
    print(num)
```

### `continue` Statement
Skips the current iteration and moves to the next one.

```python
for num in range(5):
    if num == 2:
        continue  # Skips when num is 2
    print(num)
```

### `pass` Statement
A placeholder that does nothing but allows code structure.

```python
for i in range(5):
    pass  # Placeholder for future code
```

---

## **Tasks for Students**
1. **Basic Task:** Write a `for` loop to print the first 10 natural numbers.
2. **Intermediate Task:** Write a `while` loop that prints numbers from 10 down to 1.
3. **Advanced Task:** Create a program that uses a `for` loop to iterate over a string and count the number of vowels.
4. **Challenge Task:** Write a program that prints the Fibonacci series up to `n` terms using a `while` loop.
