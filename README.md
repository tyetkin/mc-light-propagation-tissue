# Introduction to Python in Google Colab

## Getting Started with Google Colab

Google Colab is a free, cloud-based service that allows you to write, execute, and share Python code. It's an ideal platform for education, as it requires no installation and provides access to powerful computing resources.

### Accessing Google Colab
- Go to [Google Colab](https://colab.research.google.com/).
- Sign in with your Google account.
- Click on `New Notebook` to create a new Python notebook.

### Colab Interface Overview
- **Menu Bar**: Contains options for file operations, editing, and runtime controls.
- **Toolbar**: Provides quick access to common operations like running a cell, adding a new cell, and saving.
- **Code Cells**: Where you write and execute your Python code.
- **Text Cells**: For adding text, formatted using Markdown.

### Running Your First Python Code
- In a new code cell, type:
  ```python
  print("Hello, Biomedical Engineering!")
  ```
- Click the play button (▶) on the left side of the cell or press `Shift + Enter` to run the cell.
- You should see the output `Hello, Biomedical Engineering!` below the cell.

## Basic Python Syntax

### Variables and Data Types
- **Variables**: Used to store information that can be referenced and manipulated. No need to declare a type.
  ```python
  student_name = "John Doe"
  age = 20
  ```
- **Data Types**: Python has various data types including integers (`int`), floating-point numbers (`float`), strings (`str`), and booleans (`bool`).

### Operators
- Arithmetic operators (`+`, `-`, `*`, `/`, `**` for exponentiation)
- Comparison operators (`==`, `!=`, `<`, `>`, `<=`, `>=`)
- Logical operators (`and`, `or`, `not`)

### Control Structures
- **If Statements**:
  ```python
  if age > 18:
      print("Adult")
  else:
      print("Minor")
  ```
- **Loops**:
  - For loops:
    ```python
    for i in range(5):  # Iterates from 0 to 4
        print(i)
    ```
  - While loops:
    ```python
    count = 0
    while count < 5:
        print(count)
        count += 1
    ```

## Basic Data Structures

### Lists
- Ordered collections of items (arrays in other languages).
- Created using square brackets `[]`.
- Example:
  ```python
  fruits = ["apple", "banana", "cherry"]
  print(fruits[0])  # Accessing the first element, output: apple
  ```

### Tuples
- Similar to lists, but immutable (cannot be changed after creation).
- Created using parentheses `()`.
- Example:
  ```python
  dimensions = (200, 50)
  ```

### Dictionaries
- Key-value pairs, unordered, mutable.
- Created using curly braces `{}`.
- Example:
  ```python
  student = {"name": "John", "age": 20}
  print(student["name"])  # Accessing value by key, output: John
  ```

### Sets
- Unordered collections of unique elements.
- Created using curly braces `{}` or the `set()` function.
- Example:
  ```python
  colors = {"red", "green", "blue"}
  ```

## Functions
- Defined using the `def` keyword.
- Used to encapsulate a block of code that performs a specific task.
- Example:
  ```python
  def greet(name):
      return f"Hello, {name}!"

  print(greet("John"))
  ```

## Conclusion
This tutorial covered the basics of using Google Colab for Python programming, including syntax, variables, control structures, data structures, and functions. Practice these concepts to build a solid foundation in Python programming.

