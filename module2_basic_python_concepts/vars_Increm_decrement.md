## What are Variables?

Variables in Python are symbolic names that are used to store data values. They act as containers for data that can be referenced and manipulated in a program. Variables do not need explicit declaration to reserve memory space; the declaration happens automatically when you assign a value to a variable.
That's why it is called dynamically typed language.

### Examples of Variable Types in Python

#### String
Strings are sequences of characters used to represent text.

```python
first_name = "Vignan"
food1 = "biryani"
email = "biryani@1234"

# print(first_name)
# print(f"My email address is {email}")
```

#### Integer
Integers are whole numbers without a decimal point.

```python
age = 25
quantity = 3
num_of_students = 30

# print(f"You are {age} years old")
# print(f"I'm buying {quantity} packages of biryani")
# print(f"Your class has {num_of_students} students")
```

#### Float
Floats are numbers with a decimal point.

```python
price1 = 3.14
gpa = 4.2
distance = 10.5167

# print(f"The price is ${price1}")
# print(f"The GPA is {gpa}")
# print(f"I have run {distance} km")
```

#### Boolean
Booleans represent `True` or `False` values.

```python
is_student = True
for_sale = False
is_online = True

# print(f"Are you a student? {is_student}")

if not is_student:
    print("You are not a student")
else:
    print("You are a student")
```

---

## Assignment

Try the following exercises to practice working with variables and data types in Python.

### 1. Variable Declaration and Type Checking

```python
name = "vignan"
age = 25
gpa = 4.2
is_student = True

# To find the type of a variable
print(type(gpa))
print(type(is_student))

# Typecasting examples
age = str(age)
# age += 1  # This will cause an error since age is now a string

name = bool(name)
print(type(name))
print(name)
```

### 2. User Input and Type Conversion

```python
# input() prompts the user to enter data and returns it as a string

# name = input("What is your name?: ")
# age = input("How old are you?: ")
# age = int(age)
# or
# age = int(input("How old are you?: "))
# age = age + 1

# print(f"Hello {name}")
# print(f"You are {age} years old")
```

### 3. Exercise 1: Rectangle Area Calculator

Write a program to calculate the area of a rectangle using user input.

```python
length = float(input("Enter the length of the rectangle: "))
width = float(input("Enter the width of the rectangle: "))

area = length * width
print(f"The area of the rectangle is {area} cm²")
```

### 4. Exercise 2: Shopping Cart Program

Create a simple shopping cart program that takes item, price, and quantity, then calculates the total.

```python
item = "Apple"
price = 10
quantity = 5
total = price * quantity

print("Item\tQty\tPrice\tTotal")
print(f"{item}\t{quantity}\t{price}\t{total}")
```

Or display a simple table:

```python
print("Item\tQty")
print("Apple\t5")
print("Plain\t10")
```

---

Feel free to experiment with these examples and modify them to deepen your understanding of Python variables and data types!
