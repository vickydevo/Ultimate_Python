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
input() prompts the user to enter data and returns it as a string

name = input("What is your name?: ")
age = input("How old are you?: ") 
age = int(age)
# or
age = int(input("How old are you?: "))
age = age + 1

print(f"Hello {name}")
print(f"You are {age} years old")
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

### 5. Increment and Decrement Operators

In Python, you can increase or decrease the value of a variable using augmented assignment operators.

```python
friends = 0
friends = friends + 1  # Increment by 1

# Short form using augmented assignment operator
friends += 2  # Increment by 2

print(friends)  # Output: 3
```

Python does not have `++` or `--` operators like some other languages. Use `+=` to increment and `-=` to decrement.

```python
friends -= 1  # Decrement by 1
print(friends)  # Output: 2
### 6. More Examples: Augmented Assignment Operators

Here are more examples demonstrating how to use augmented assignment operators in Python:

```python

# Decrement by 2
friends = friends - 2

# Decrement by -2 (effectively adds 2)
friends -= -2

# Multiply by 3
friends = friends * 3
friends *= 3

# Divide by 2
friends /= 2

# Exponentiation (raise to the power of 2)
friends = friends ** 2
friends **= 2

# Modulo operation: remainder when divided by 3
remainder = friends % 3

print(remainder)
```

**Output:**
```
2
```
# Math Functions Example

This code demonstrates the usage of several built-in Python mathematical functions:

- `round(x)`: Rounds the floating-point number `x` to the nearest integer.
- `abs(y)`: Returns the absolute value of `y`, which is the distance from zero.
- `pow(a, b)`: Calculates `a` raised to the power of `b` (i.e., `a ** b`).
- `max(x, y, z)`: Returns the largest value among the given arguments.
- `min(x, y, z)`: Returns the smallest value among the given arguments.

The final result printed will be the outcome of the last operation assigned to `result`.

```python
import math

x = 9.2
y = 9.9

# math.pi: The mathematical constant π (pi), approximately 3.14159.
# math.e: The mathematical constant e, the base of natural logarithms, approximately 2.71828.
# math.sqrt(x): Returns the square root of x.
# math.ceil(x): Returns the smallest integer greater than or equal to x.
# math.floor(y): Returns the largest integer less than or equal to y.

print(math.pi)         # Output: 3.141592653589793
print(math.e)          # Output: 2.718281828459045
print(math.sqrt(x))    # Output: 3.03315017762062
print(math.ceil(x))    # Output: 10
print(math.floor(y))   # Output: 9
```

#### Circumference of a Circle Example

The circumference of a circle is calculated as:

```
Circumference = 2 * π * radius
```

Example in Python:

```python
import math

radius = float(input("Enter the radius: "))
circumference = 2 * math.pi * radius
print(f"The circumference of the circle is {round(circumference, 2)}cm²")
```

**Output:**
```
The circumference of the circle is 31.41592653589793
```


