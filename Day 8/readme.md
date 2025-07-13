# ARTIFICIAL INTELLIGENCE AND MACHINE LEARNING  
**DAY - 8**

**Date:** 2 July 2025  

---

## Strings

Strings in Python are sequences of characters and are enclosed in either:

- **Single quotes**: `'hello'`
- **Double quotes**: `"hello"`

Both are treated the same in Python:

```python
print('hello')     # Output: hello
print("hello")     # Output: hello
```
---

## Slicing Strings

You can return a **range of characters** from a string using the **slice syntax**:

```python
# Syntax: string[start:end]
text = "Artificial"
print(text[2:5])  # Output: 'tif'
```

---

## String Concatenation

To concatenate, or combine, two strings, you can use the `+` operator:

```python
greeting = "Hello, "
name = "World"
message = greeting + name
print(message)  # Output: Hello, World
```

---

## Python Operators

Operators are used to perform operations on variables and values.  
Python divides the operators into the following groups:

- **Arithmetic operators**  
- **Assignment operators**  
- **Comparison operators**  
- **Logical operators**  
- **Identity operators**  
- **Membership operators**  
- **Bitwise operators**  

### Operator Precedence

Operator precedence describes the order in which operations are performed.  
For example, multiplication (`*`) has higher precedence than addition (`+`), so it’s evaluated first.

---
## List

Lists are used to store multiple items in a single variable.  
Lists are one of the four built-in data types in Python used to store collections of data. The other three are Tuple, Set, and Dictionary—each with different qualities and usage.

Lists are created using square brackets:

```python
my_list = [item1, item2, item3]
```

### List Length

To determine how many items a list has, use the `len()` function:

```python
my_list = [1, 2, 3, 4]
print(len(my_list))  # Output: 4
```

### Access Items

List items are indexed and you can access them by referring to the index number:

```python
fruits = ['apple', 'banana', 'cherry']
print(fruits[0])  # Output: apple
print(fruits[1])  # Output: banana
```

### Change Item Value

To change the value of a specific item, refer to the index number:

```python
fruits = ['apple', 'banana', 'cherry']
fruits[1] = 'blueberry'
print(fruits)  # Output: ['apple', 'blueberry', 'cherry']
```

### Append Items

To add an item to the end of the list, use the `append()` method:

```python
fruits = ['apple', 'banana', 'cherry']
fruits.append('orange')
print(fruits)  # Output: ['apple', 'banana', 'cherry', 'orange']
```

### Remove Specified Item

The `remove()` method removes the specified item from the list:

```python
fruits = ['apple', 'banana', 'cherry', 'orange']
fruits.remove('banana')
print(fruits)  # Output: ['apple', 'cherry', 'orange']
```
---

## Tuple

Tuples are used to store multiple items in a single variable.  
Tuple is one of the 4 built-in data types in Python used to store collections of data, the other 3 being List, Set, and Dictionary, all with different qualities and usage.  

A tuple is a collection which is **ordered** and **unchangeable** (immutable).  
Tuples are written with round brackets `()`.

Example:

```python
my_tuple = (1, 2, 3, "apple", "banana")
print(my_tuple)
```

---

## Set

Sets are used to store multiple items in a single variable.  
Set is one of the 4 built-in data types in Python used to store collections of data, the other 3 being List, Tuple, and Dictionary, all with different qualities and usage.  

A set is a collection which is **unordered**, **unchangeable**, and **unindexed**.

Example:

```python
my_set = {"apple", "banana", "cherry"}
print(my_set)
```

---

## Dictionary

Dictionaries are used to store data values in key:value pairs.  
A dictionary is a collection which is **ordered***, **changeable**, and does **not allow duplicates**.  
Dictionaries are written with curly brackets, and have keys and values:

Example:

```python
my_dict = {
    "name": "Alice",
    "age": 25,
    "city": "New York"
}
print(my_dict)
```

---

## Python Conditions and If Statements

Python supports the usual logical conditions from mathematics:

- Equals: `a == b`
- Not Equals: `a != b`
- Less than: `a < b`
- Less than or equal to: `a <= b`
- Greater than: `a > b`
- Greater than or equal to: `a >= b`

These conditions can be used in several ways, most commonly in **if statements** and loops.  
An **if statement** is written using the `if` keyword:

```python
if a > b:
    print("a is greater than b")
elif a == b:
    print("a is equal to b")
else:
    print("a is less than b")
```

## The while Loop

With the **while** loop, we can execute a set of statements **as long as a condition is true**.

Example:

```python
i = 1
while i <= 5:
    print(i)
    i += 1
```

## Python For Loops

A **for loop** is used for iterating over a sequence (such as a list, tuple, dictionary, set, or string).  
This is less like the traditional for keyword in other programming languages and works more like an iterator method found in other object-oriented languages.

With the **for loop**, we can execute a set of statements once for each item in the sequence.

Example:

```python
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)
```

---

## Python Functions

A **function** is a block of code that only runs when it is called.  
You can pass data, known as **parameters**, into a function.  
A function can also return data as a result.

### Defining a Function

```python
def greet(name):
    print(f"Hello, {name}!")
```


