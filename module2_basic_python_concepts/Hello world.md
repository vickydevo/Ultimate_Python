# Why Should We Code?

Coding is a fundamental skill in today's digital world. Here are a few reasons why learning to code is important:

- **Problem Solving:** Coding teaches you how to break down complex problems and find logical solutions.
- **Creativity:** It allows you to build your own applications, games, and websites from scratch.
- **Career Opportunities:** Many high-demand jobs require programming skills.
- **Automation:** Coding helps automate repetitive tasks, saving time and effort.
- **Understanding Technology:** It gives you a deeper understanding of how software and devices work.

Whether you want to pursue a career in tech or simply understand the world better, coding is a valuable skill to learn.

## What is REPL in Python?

REPL stands for **Read-Eval-Print Loop**. It's an interactive environment where you can type Python code, have it executed immediately, and see the result.

For example, you can enter the following in a Python REPL:

```python 
'hello world'

repr ( 'hello world') 

```

This will display the prompt `hello world ` and wait for your input.

## Mathematical Operations in Python  

## Sample Python REPL Session

Below is an example of how you can perform mathematical operations in the Python REPL:

```
>>> 1+5
6
>>> 6-3
3
>>> 9/3
3.0
>>> 20/3
6.666666666666667
>>> 20//3
6
>>> 20%3
2
>>> 20*5
100
>>> 2*2*2*2
16
>>> 2**4
16
>>> 3*5+2
17
>>> 3*(5+2)
21
>>>
```
## Structure of Mathematical Operations: operands and operators

In Python, a mathematical operation consists of:

- **Operands:** The values or variables being operated on (e.g., `3`, `5`, `2`).
- **Operators:** The symbols that specify the operation (e.g., `+`, `-`, `*`, `/`, `//`, `%`, `**`).

### Examples from above:

- `20 // 3`  
    - Operands: `20`, `3`
    - Operator: `//` (floor division)

- `2 ** 4`  
    - Operands: `2`, `4`
    - Operator: `**` (exponentiation)



These examples show how operands and operators combine to form mathematical expressions in Python.


## What is a String in Python?

A **string** in Python is a sequence of characters enclosed in single quotes (`'...'`), double quotes (`"..."`), or triple quotes (`'''...'''` or `"""..."""`). Strings are used to represent text data.


### Printing Strings in Python

You can print strings in Python using either single quotes (`'...'`) or double quotes (`"..."`). Both work the same way, but using different quotes can help when your string contains quote characters.

#### Examples:

```python
print('Python\'s"world"')      # Output: Python's"world"
print("Python's world")        # Output: Python's world
print('Python\'s ' 'world')    # Output: Python's world
```
You can also concatenate string literals by placing them next to each other, as shown in the last example.


### Example:

```python
message = "Hello, World!"
name = 'Alice'
multiline = """This is
a multiline
string."""
```

## Common String Methods

Python provides many built-in methods to work with strings. Here are some commonly used ones:

- `.capitalize()` – Capitalizes the first character.
- `.strip()` – Removes leading and trailing whitespace.
- `.replace(old, new)` – Replaces occurrences of a substring.
- `.split(separator)` – Splits the string into a list.
- `.find(substring)` – Returns the index of the first occurrence of a substring.

### Examples:

```python
text = "  Hello, Python!  "

print(text.upper())        # '  HELLO, PYTHON!  '
print(text.lower())        # '  hello, python!  '
print(text.strip())        # 'Hello, Python!'
print(text.replace("Python", "World"))  # '  Hello, World!  '
print(text.split(","))     # ['  Hello', ' Python!  ']
print(text.find("Python")) # 9
```

Strings are immutable, meaning their contents cannot be changed after creation. String methods return new string objects with the desired modifications.


## What is the `input()` Function and Why Do We Use It?

The `input()` function in Python is used to get user input from the keyboard. When you call `input()`, the program pauses and waits for the user to type something and press Enter. The function then returns the entered data as a string.

### Why Use `input()`?

- **Interactivity:** It allows your programs to interact with users by accepting data at runtime.
- **Flexibility:** You can write programs that respond to user choices or data.
- **Dynamic Behavior:** Input makes your scripts more flexible and adaptable to different situations.

### Example

```python
name = input("What is your name? ")
print("Hello, " + name + "!")
```

You said:
>>> name = input("What is your name? ")
What is your name? vignan
>>> print(name)
vignan
>>> print('Hello', name)
Hello vignan
>>> print("Item\t Qty \nApple\t 5\nPlain\t 10")
Item     Qty
```
>>> name = input("What is your name? ")
What is your name? vignan
>>> print(name)
vignan
>>> print('Hello', name)
Hello vignan
>>> print("Item\t Qty \nApple\t 5\nPlain\t 10")
Item     Qty 
Apple    5
Plain    10
```

The above session demonstrates how to use the `input()` function to interact with the user and how to print formatted output using escape characters like `\t` (tab) and `\n` (newline).
When you run this code, it will prompt the user to enter their name and then greet them using the provided input.