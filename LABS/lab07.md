
# Functions in Python

Functions are blocks of reusable code that perform a specific task. They help in organizing code, improving readability, and avoiding repetition.

---

## 1. Defining a Function

To define a function in Python, use the `def` keyword:

```python
def greet():
    print("Hello, welcome to Python functions!")
```

To **call** this function:

```python
greet()
```

---

## 2. Function with Parameters

Functions can take parameters to make them more flexible.

```python
def greet_user(name):
    print(f"Hello, {name}! Nice to meet you.")
```

Calling it with a value:

```python
greet_user("Alice")
```

---

##  3. Function with Return Value

You can return values from functions using the `return` keyword:

```python
def add(a, b):
    return a + b
```

Calling and storing the result:

```python
result = add(5, 3)
print("Sum is:", result)
```

---

##  4. Default Parameters

You can provide default values for parameters:

```python
def greet(name="Guest"):
    print(f"Hello, {name}!")
```

```python
greet()           # Output: Hello, Guest!
greet("Zara")     # Output: Hello, Zara!
```

---

##  Tasks

###  Task 1: Write a function that takes two numbers and returns their product.


###  Task 2: Write a function that checks whether a number is even or odd.

###  Task 3: Write a function that takes a name and age and prints a greeting.




---
