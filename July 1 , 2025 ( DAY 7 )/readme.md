# ARTIFICIAL INTELLIGENCE AND MACHINE LEARNING  
**DAY - 7**

**Date:** 1 July 2025  

---

## Vim

Vim (short for Vi IMproved) is a highly configurable, efficient, and powerful text editor built for use in the terminal. It's an improved version of the classic UNIX editor Vi, and it’s a favorite among developers, sysadmins, and power users.

### Modes in Vim:
- **Normal mode**: for navigation and commands  
- **Insert mode**: for typing/editing text  
- **Visual mode**: for selecting text  
- **Command-line mode**: for saving, quitting, etc.

---

### Step-by-Step Installation

1. **Update package list**
   ```bash
   sudo apt update
   ```

2. **Install Vim**
   ```bash
     sudo apt install vim 
   ```
---

### Vim Workflow

1.	**Open Terminal**
Launch the terminal in Ubuntu.

2.	**Open or Create a File**
```bash
vim filename.py
```
If the file exists, it opens for editing. If not, Vim creates it.

3.	**Enter Insert Mode to Start Editing**
   
•	Press i to enter Insert mode

•	Now you can type or edit text.

4.	**Exit Insert Mode**
   
•	Press Esc to go back to Normal mode.

5.	**Save and Quit**
   
•	Press : to enter Command mode, then type:

  ->:w → Save (write) the file
   
  ->:q → Quit
   
  ->:wq → Save and quit
   
  ->:q! → Quit without saving
   

9.	**Run the File (Example: Python Script)**
   ```bash
python3 filename.py
   ```
---

## Kaggle

Kaggle is an online platform that serves as a central hub for data science and machine learning practitioners.  
It offers a wide range of resources, including:  
- Real-world datasets  
- Cloud-based coding environments (called **Kaggle Notebooks**)  
- Educational courses  
- A strong data science and ML community  

---

## Python

Python is a high-level, interpreted, general-purpose programming language known for its **simplicity**, **readability**, and **versatility**.  

Created by **Guido van Rossum** and first released in **1991**, Python has become one of the most popular programming languages in the world.

### Python is widely used in:
- Web development (using frameworks like Django, Flask)  
- Data science & machine learning (with pandas, NumPy, TensorFlow)  
- Automation and scripting  
- Software development  

---

## Python Syntax and Execution

Python syntax can be executed directly by writing code into the **Command Line**:

```bash
python3
```

Then type Python code like:
```bash
print("Hello, World!")
```
---

## Python Indentation

Indentation refers to the **spaces at the beginning of a code line**.

In most programming languages, indentation is used for readability only.  
**In Python, indentation is mandatory** — it defines blocks of code.

Example:

```python
if 5 > 2:
    print("Five is greater than two!")
```

## Comments in Python

Python has commenting capability for the purpose of **in-code documentation**.  
Comments start with a `#`, and Python ignores everything after the `#` on that line.

### Example:
```python
# This is a comment
print("Hello, World!")
```

## Variables

**Variables** are containers for storing data values in Python.

---

### Creating Variables

Python does **not** require a special command to declare a variable.  
A variable is created the **moment you assign a value** to it.

### Example:
```python
x = 10
name = "John"
is_active = True
```

## Variable Names

A variable can have a **short name** (like `x` or `y`) or a more **descriptive name** (like `age`, `car_name`, or `total_volume`).

### Rules for Naming Variables in Python:

- A variable name **must start** with a letter (A–Z or a–z) or an underscore (`_`)
- A variable name **cannot start with a number**
- A variable name **can only contain** alphanumeric characters and underscores (`A–Z`, `a–z`, `0–9`, and `_`)
- Variable names are **case-sensitive** (`age`, `Age`, and `AGE` are all different variables)
- A variable name **cannot be a Python keyword** (like `if`, `while`, `class`, etc.)

---

## Built-in Data Types

In programming, a **data type** defines the kind of value a variable holds and what operations can be performed on it.

## Casting in Python

There may be times when you want to **explicitly specify a data type** for a variable.  
This is done using **type casting**, also known as type conversion.

Python is an **object-oriented language**, and it uses **classes** to define data types, including its primitive types.

### Type Casting with Constructor Functions:

- `int()` — Converts a value to an **integer**
- `float()` — Converts a value to a **float**
- `str()` — Converts a value to a **string**

### Examples:

```python
x = int("5")       # x will be 5 (integer)
y = float("3.14")  # y will be 3.14 (float)
z = str(42)        # z will be "42" (string)
```


**By**  : Aditi Tangri

**URN**  : 2302460  

**CRN**  : 2315004
