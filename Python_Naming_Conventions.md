# Naming Conventions in Python

## What are Naming Conventions in Python?

Naming conventions are rules and guidelines for naming variables, functions, classes, and other objects in Python.

They make code easy to read and understand.

## 1. Variable Naming Convention

We use lowercase letters to name variables. If a name contains multiple words, we use an underscore `_` between words.

**Example:**

```python
student_name = "Rishabh"
student_age = 22
total_marks = 450
```

## 2. Function Naming Convention

Function names should use lowercase letters. We use underscores to separate multiple words.

**Example:**

```python
def calculate_total():
    print("Calculating total")

calculate_total()
```

**Output:**

```text
Calculating total
```

## 3. Class Naming Convention

Class names usually use CapWords, also called PascalCase. Each word starts with a capital letter.

**Example:**

```python
class StudentDetails:
    pass
```

Here, `StudentDetails` is a class name.

## 4. Constant Naming Convention

Constant names are usually written in uppercase letters. We use underscores between words.

**Example:**

```python
MAX_MARKS = 100
PI_VALUE = 3.14
```

Python does not strictly enforce constants. Uppercase names are a naming convention that tells developers the value should not be changed.

## 5. Rules for Naming Identifiers

1. A name can contain letters, numbers, and underscores.
2. A name cannot start with a number.
3. Spaces are not allowed in names.
4. Python keywords cannot be used as names.
5. Names are case-sensitive.
6. Use meaningful names that explain their purpose.

## Examples of Valid Names

```python
name = "Rishabh"
student_age = 22
_marks = 90
total2 = 200
```

## Examples of Invalid Names

```python
# 2name = "Rishabh"
# student-name = "Rahul"
# student name = "Amit"
```

These names are invalid because names cannot start with a number or contain hyphens or spaces.

## Advantages of Naming Conventions

1. They make code easy to read.
2. They make code easy to understand.
3. They improve code consistency.
4. They help developers maintain code.

## Interview Question

**Q. What are naming conventions in Python?**

**Answer:**

Naming conventions are rules for naming variables, functions, and classes in Python. They make code easy to read and understand. For example, we use `student_name` for a variable, `calculate_total()` for a function, and `StudentDetails` for a class.