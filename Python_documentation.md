# 📚 Python Mastery: Beginner to Advanced by Niloy Bhuiyan

---

## 1. 📘 Introduction to Python

### History
- Created by Guido van Rossum in 1991.
- Named after "Monty Python" (not the snake!).
- Designed to be easy-to-read and powerful.

### Features
- Easy to learn, write, and understand.
- Huge standard library.
- Dynamically typed.
- Portable and interpreted.
- Supports OOP and Functional programming.

### Applications
- Web development (Django, Flask)
- Data Science (Pandas, NumPy)
- Machine Learning (Scikit-learn, TensorFlow)
- Automation and scripting
- Game development
- IoT and Robotics

---

## 2. 🛠️ Installation Guide

### Installing Python
- Visit python.org
- Download and install the latest version.
- Tick "Add Python to PATH" during installation.

### IDEs (Recommended)
- PyCharm
- VS Code
- Jupyter Notebook
- IDLE (comes with Python)

### Setting up a Virtual Environment
```bash
# Install virtualenv
pip install virtualenv

# Create a virtual environment
virtualenv myenv

# Activate
# Windows
myenv\Scripts\activate
# Mac/Linux
source myenv/bin/activate
```
✅ **Mini Task:** Install Python and set up VS Code.

---

## 3. 🧱 Basic Syntax and Structure

### Comments
```python
# This is a comment
```

### Indentation
- Python uses indentation (spaces or tabs) to define blocks.
```python
if True:
    print("Hello World")
```

### Input and Output
```python
name = input("Enter your name: ")
print("Hello,", name)
```

✅ **Mini Task:** Write a program that asks for your name and age.

---

## 4. 🧮 Data Types and Variables

| Data Type | Example       |
|-----------|---------------|
| int       | 5             |
| float     | 3.14          |
| str       | "Hello"       |
| list      | [1, 2, 3]     |
| tuple     | (1, 2, 3)     |
| set       | {1, 2, 3}     |
| dict      | {"a": 1, "b": 2} |

```python
x = 10
y = 3.14
z = "Python"
list1 = [1, 2, 3]
```

✅ **Mini Task:** Create variables of different types.

---

## 5. ➗ Operators

### Arithmetic Operators
```python
print(5 + 2)  # Addition
print(5 - 2)  # Subtraction
print(5 * 2)  # Multiplication
print(5 / 2)  # Division
print(5 % 2)  # Modulus
```

### Logical Operators
```python
print(True and False)  # False
print(True or False)   # True
print(not True)        # False
```

✅ **Mini Task:** Create a calculator for +, -, *, /.

---

## 6. 🔀 Conditional Statements

### Example
```python
age = 18
if age >= 18:
    print("Adult")
else:
    print("Minor")
```

### if-elif-else
```python
marks = 85
if marks >= 90:
    print("A+")
elif marks >= 80:
    print("A")
else:
    print("Below A")
```

✅ **Mini Task:** Write a program that checks if a number is positive, negative, or zero.

---

## 7. 🔁 Loops

### for Loop
```python
for i in range(5):
    print(i)
```

### while Loop
```python
i = 0
while i < 5:
    print(i)
    i += 1
```

✅ **Mini Task:** Print numbers 1 to 10.

---

## 8. 🛎️ Functions

### Example
```python
def greet(name):
    return f"Hello, {name}!"

print(greet("Niloy"))
```

### *args and **kwargs
```python
def add(*numbers):
    return sum(numbers)

def person(**info):
    return info
```

✅ **Mini Task:** Create a function that multiplies 3 numbers.

---

## 9. 🧩 Object-Oriented Programming (OOP)

### Class and Object
```python
class Dog:
    def __init__(self, name):
        self.name = name
    
    def bark(self):
        print(f"{self.name} says Woof!")

dog1 = Dog("Buddy")
dog1.bark()
```

✅ **Mini Task:** Create a Car class.

---

## 10. 🚨 Exception Handling
```python
try:
    x = 5 / 0
except ZeroDivisionError:
    print("Cannot divide by zero!")
finally:
    print("Done")
```

✅ **Mini Task:** Handle an error when accessing an undefined variable.

---

## 11. 📁 File Handling

### Writing to a file
```python
with open("test.txt", "w") as file:
    file.write("Hello, World!")
```

### Reading a file
```python
with open("test.txt", "r") as file:
    print(file.read())
```

✅ **Mini Task:** Create a file and write your name.

---

## 12. 📦 Modules and Packages
```python
import math
print(math.sqrt(16))
```

### pip Usage
```bash
pip install numpy
```

✅ **Mini Task:** Install requests library.

---

## 13. 🏛️ Important Standard Libraries
- **os:** interacting with operating system
- **sys:** system-specific parameters
- **datetime:** dates and times
- **random:** random numbers
- **json:** working with JSON data
- **re:** regular expressions

✅ **Mini Task:** Use random to generate a random number between 1 and 100.

---

## 14. 🚀 Advanced Topics

### Decorators
```python
def decorator(func):
    def wrapper():
        print("Before function")
        func()
        print("After function")
    return wrapper

@decorator
def say_hello():
    print("Hello!")

say_hello()
```

### Generators
```python
def gen():
    for i in range(3):
        yield i

for val in gen():
    print(val)
```

✅ **Mini Task:** Create a generator for even numbers till 10.

---

## 15. 📋 Mini Projects and Practice Tasks

### Project Ideas:
- Simple Calculator (CLI based)
- To-Do List App
- Web Scraper for Quotes
- Weather App using API

✅ **Mini Task:** Start a "To-Do List" app using Python!

---

## 16. 🌟 Motivational Tips for Learners
- Practice a little every day.
- Build small projects.
- Solve real-world problems.
- Never give up when stuck.
- Enjoy the learning journey 🚀

---

🎯 **End of Documentation**

> "The expert in anything was once a beginner. Keep coding, keep growing!"
```

---
