# Python Data Types

## What are Data Types in Python?

Data types tell us what type of data we store in a variable.

Python has different data types to store numbers, text, and other values.

For example, 10 is a number and "Hello" is text.

## Types of Data Types in Python

Python has different built-in data types. Here are some common types:

### 1. Integer (int)

An integer is a whole number.

**Example:**

```python
age = 22
print(age)
```

**Output:**

```text
22
```

### 2. Float (float)

A float is a number with a decimal point.

**Example:**

```python
price = 10.5
print(price)
```

**Output:**

```text
10.5
```

### 3. String (str)

A string is text written inside quotes.

**Example:**

```python
name = "Rishabh"
print(name)
```

**Output:**

```text
Rishabh
```

### 4. Boolean (bool)

A Boolean has two values: True or False.

**Example:**

```python
is_student = True
print(is_student)
```

**Output:**

```text
True
```

### 5. List (list)

A list stores multiple values in one variable. We can change its values.

**Example:**

```python
fruits = ["Apple", "Mango", "Banana"]
print(fruits)
```

**Output:**

```text
['Apple', 'Mango', 'Banana']
```

### 6. Tuple (tuple)

A tuple stores multiple values. We cannot change its items after creation.

**Example:**

```python
colors = ("Red", "Green", "Blue")
print(colors)
```

**Output:**

```text
('Red', 'Green', 'Blue')
```

### 7. Set (set)

A set stores unique values. It does not keep duplicate values.

**Example:**

```python
numbers = {10, 20, 10, 30}
print(numbers)
```

**Output:**

```text
{10, 20, 30}
```

### 8. Dictionary (dict)

A dictionary stores data in key-value pairs.

**Example:**

```python
student = {"name": "Rishabh", "age": 22}
print(student)
```

**Output:**

```text
{'name': 'Rishabh', 'age': 22}
```

## How to Check Data Types?

We use the `type()` function to check the type of data.

**Example:**

```python
age = 22
print(type(age))
```

**Output:**

```text
<class 'int'>
```

## Interview Questions

### Q1. What are data types in Python?

**Answer:**

Data types tell us what type of data a variable stores. For example, integer stores whole numbers, float stores decimal numbers, and string stores text.

### Q2. What are the common data types in Python?

**Answer:**

Some common data types are integer, float, string, Boolean, list, tuple, set, and dictionary.

### Q3. How can we check the data type?

**Answer:**

We use the `type()` function to check the data type of a variable.

## Conclusion

Data types help us store different types of data in Python. They make it easy to work with numbers, text, and multiple values.