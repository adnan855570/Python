
# Python Basics Notebook

Welcome to the **Python Basics** repository!  
This notebook is a step-by-step, hands-on walkthrough of Python’s foundational concepts, aimed at beginners and those brushing up their skills. Each section covers a key Python topic, with code examples and explanations you can run and modify.

---

## Table of Contents

1. [Data Types & Operators](#1-data-types--operators)
2. [Boolean Data Type](#2-boolean-data-type)
3. [Operators in Python](#3-operators-in-python)
    - Addition, Subtraction, Multiplication, Division, Floor Division, Modulus, Exponent
4. [String Operations](#4-string-operations)
5. [Type Casting](#5-type-casting)
6. [Input/Output](#6-inputoutput)
7. [Lists](#7-lists)
8. [Tuples](#8-tuples)
9. [Dictionaries](#9-dictionaries)
10. [Sets](#10-sets)
11. [Control Statements](#11-control-statements)
    - if/else, for, while
12. [Functions](#12-functions)
13. [File Handling](#13-file-handling)
14. [Exception Handling](#14-exception-handling)
15. [Object-Oriented Programming](#15-object-oriented-programming)
    - Classes & Objects, Inheritance
16. [Lambdas and Iterators](#16-lambdas-and-iterators)

---

## 1. Data Types & Operators

Understand variables and how Python stores different types of data.

```python
message = "Welcome"
number = '11'
print(message, number)
print(type(message))
print(type(number))

secondNumber = 11
print(type(secondNumber))
```

**Explanation:**  
- Strings: Text data, wrapped in quotes (`"..."` or `'...'`)
- Integers: Whole numbers (no quotes)
- `type()` tells you what type of data you’re working with.

---

## 2. Boolean Data Type

Python uses booleans for logic — `True` or `False`.

```python
yes = True
print(yes)
print(type(yes))
```

**Why it matters:**  
Booleans power every conditional check (`if`, `while`, etc.).

---

## 3. Operators in Python

Arithmetic, assignment, comparison, and logical operators.

### Arithmetic Example: Addition

```python
x = 10
y = 20
print(x + y)
```

### Other Arithmetic Operators

```python
# Subtraction
print(x - y)
# Multiplication
print(x * y)
# Division
print(x / y)
# Floor Division
print(x // y)
# Modulus
print(x % y)
# Exponentiation
print(x ** 2)
```

**Use case:**  
Do math, calculate values, drive program logic.

---

## 4. String Operations

Work with text: concatenate, slice, and manipulate strings.

```python
first = "Hello"
second = "World"
print(first + " " + second)
print(first[0:3])  # Slicing: get 'Hel'
```

---

## 5. Type Casting

Convert between data types easily.

```python
num = "123"
converted = int(num)
print(converted)
print(type(converted))
```

---

## 6. Input/Output

Interact with the user.

```python
name = input("Enter your name: ")
print("Hello,", name)
```

---

## 7. Lists

Ordered, mutable collections.

```python
mylist = [1, 2, 3, "Python"]
print(mylist)
print(mylist[2])    # Access element
mylist.append(4)    # Add element
print(mylist)
```

---

## 8. Tuples

Ordered, immutable collections.

```python
mytuple = (1, 2, 3, "Python")
print(mytuple)
```

---

## 9. Dictionaries

Key-value storage, like a map.

```python
mydict = {"name": "Alice", "age": 22}
print(mydict)
print(mydict["name"])
```

---

## 10. Sets

Unordered, unique items.

```python
myset = {1, 2, 3, 3, 2}
print(myset)  # Outputs: {1, 2, 3}
```

---

## 11. Control Statements

### If/Else

```python
age = 18
if age >= 18:
    print("Adult")
else:
    print("Minor")
```

### For Loop

```python
for i in range(5):
    print(i)
```

### While Loop

```python
count = 0
while count < 3:
    print(count)
    count += 1
```

---

## 12. Functions

Reusable blocks of code.

```python
def greet(name):
    print("Hello,", name)

greet("Alice")
```

---

## 13. File Handling

Read and write files.

```python
with open("file.txt", "w") as f:
    f.write("Hello, file!")
```

---

## 14. Exception Handling

Gracefully handle errors.

```python
try:
    x = 10 / 0
except ZeroDivisionError:
    print("You can't divide by zero!")
```

---

## 15. Object-Oriented Programming

### Classes & Objects

```python
class Dog:
    def __init__(self, name):
        self.name = name

    def bark(self):
        print(self.name, "says woof!")

mydog = Dog("Rex")
mydog.bark()
```

### Inheritance

```python
class Animal:
    def speak(self):
        print("Animal speaks")

class Dog(Animal):
    def speak(self):
        print("Dog barks")

d = Dog()
d.speak()
```

---

## 16. Lambdas and Iterators

### Lambda Functions

```python
add = lambda a, b: a + b
print(add(2, 3))
```

### Iterators

```python
mylist = [1, 2, 3]
it = iter(mylist)
print(next(it))
print(next(it))
```

---

## How to Use This Notebook

- **Clone this repo**
- Open `Python_Basics.ipynb` in [Jupyter Notebook](https://jupyter.org/) or [Google Colab](https://colab.research.google.com/)
- Run each cell and edit code to experiment with concepts
- Use this notebook as a reference, playground, or for interviews

---

## Why This Matters

Python is the fastest-growing language for a reason: simplicity, power, and endless use-cases.  
This notebook gives you a real jump-start, from zero to hands-on.

---

## Contributing

Found a bug, typo, or have a suggestion? Open an issue or submit a pull request.

---

## License

This repo is open source, for learning and personal/professional use. No restrictions—just don’t plagiarize without credit.

