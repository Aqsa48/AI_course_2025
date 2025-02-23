# Python Data Types

Python provides various built-in data types to store and manipulate different kinds of data. Below is a list of common data types along with example Python code.

## 1. Numeric Types

### Integer (int)
```python
num1 = 10  # Integer
num2 = -5  # Negative Integer

# Type Casting
float_num = float(num1)  # Convert int to float
```

### Floating-point (float)
```python
pi = 3.14  # Float
negative_float = -2.5  # Negative Float

# Type Casting
int_pi = int(pi)  # Convert float to int
```

### Complex (complex)
```python
z1 = 2 + 3j  # Complex number
z2 = 4 - 2j  # Another Complex number

# Type Casting
z_real = z1.real  # Extract real part
```

## 2. Sequence Types

### String (str)
```python
text1 = "Hello, Python!"  # String
text2 = 'Learning is fun'  # Another String

# Type Casting
char_list = list(text1)  # Convert string to list
```

### List (list)
```python
numbers = [1, 2, 3, 4]  # List
mixed_list = [1, "hello", 3.5]  # List with mixed data types

# Type Casting
tuple_numbers = tuple(numbers)  # Convert list to tuple
```

### Tuple (tuple)
```python
coordinates = (10, 20)  # Tuple
values = (1, 2, 3, 4)  # Another Tuple

# Type Casting
list_values = list(values)  # Convert tuple to list
```

### Range (range)
```python
r1 = range(5)  # Range from 0 to 4
r2 = range(1, 10, 2)  # Range with step

# Type Casting
range_list = list(r1)  # Convert range to list
```

## 3. Set Types

### Set (set)
```python
unique_numbers = {1, 2, 3, 3}  # Set (duplicates removed)
char_set = {'a', 'b', 'c'}  # Set of characters

# Type Casting
set_list = list(unique_numbers)  # Convert set to list
```

### Frozen Set (frozenset)
```python
frozen = frozenset([1, 2, 3])  # Immutable Set
frozen_chars = frozenset('abc')  # Frozen set of characters

# Type Casting
frozen_list = list(frozen)  # Convert frozenset to list
```

## 4. Mapping Type

### Dictionary (dict)
```python
person = {"name": "Alice", "age": 25}  # Dictionary
student = {"id": 101, "grade": "A"}  # Another Dictionary

# Type Casting
dict_keys = list(person.keys())  # Convert dictionary keys to list
```

## 5. Boolean Type

### Boolean (bool)
```python
is_python_fun = True  # Boolean value
is_raining = False  # Another Boolean value

# Type Casting
bool_num = bool(1)  # Convert integer to boolean
```

## 6. Binary Types

### Bytes (bytes)
```python
byte_data = b"hello"  # Bytes
byte_seq = bytes([65, 66, 67])  # Bytes from ASCII values

# Type Casting
byte_list = list(byte_data)  # Convert bytes to list
```

### Bytearray (bytearray)
```python
mutable_bytes = bytearray([65, 66, 67])  # Mutable Bytes
byte_arr = bytearray(b"Python")  # Another Bytearray

# Type Casting
byte_str = mutable_bytes.decode()  # Convert bytearray to string
```

### Memoryview (memoryview)
```python
memory = memoryview(bytes(5))  # Memory view
mem_from_bytes = memoryview(b"data")  # Another Memory view

# Type Casting
mem_list = list(memory)  # Convert memoryview to list
```

## 7. None Type

### NoneType (None)
```python
empty_value = None  # Represents no value
not_defined = None  # Another NoneType

# Type Casting
none_str = str(empty_value)  # Convert None to string
```
