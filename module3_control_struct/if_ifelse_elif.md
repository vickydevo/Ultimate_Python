# If, Else, and Elif Statements in Python

Conditional statements allow you to execute code only if certain conditions are met. The basic structure uses `if`, `elif`, and `else` keywords.


## Example: Name Input

```python
name = input("Enter your name: ")

if name == "":
    print("You did not type your name")
else:
    print(f"Your name is {name}")
```

- Checks if the user entered a name.

## Example: Online Status

```python
online = False

if online:
    print("User is online")
else:
    print("User is offline")
```

- Checks the value of the `online` variable and prints the user's status.

## Example: Age Verification

```python
age = int(input("Enter your age: "))

if age >= 100:
    print("You are too old to sign up")
elif age >= 18:
    print("You are now signed up for a credit card")
elif age < 0:
    print("You haven't been born yet")
else:
    print("You must be 18+ to sign up")
```

- The program checks the user's age and prints a message based on the value entered.
- Note: The condition `elif age >= 100` is redundant after the first `if age >= 100:`.

---

**Tip:**  
Use `if`, `elif`, and `else` to control the flow of your Python programs based on conditions.

## Calculator Exercise

Create a simple calculator that performs addition, subtraction, multiplication, or division based on user input.

```python
operator = input("Enter an operator (+,-,/,*): ")

num1 = float(input("Enter the 1st number: "))
num2 = float(input("Enter the 2nd number: "))

if operator == "+":
    result = num1 + num2
    print(result)
elif operator == "-":
    result = num1 - num2
    print(result)
elif operator == "/":
    result = num1 / num2
    print(result)
else:
    result = num1 * num2
    print(result)
```

- Prompts the user to enter an operator and two numbers.
- Performs the selected operation and prints the result.
- Uses `if`, `elif`, and `else` statements to control the flow based on the operator entered.

## Temperature Conversion

Convert temperatures between Celsius and Fahrenheit using conditional statements.

```python
unit = input("Enter the temperature measure in F/C: ").upper()
temp = float(input("Enter temp value: "))

if unit == "C":
    fahrenheit = round((temp * 9 / 5) + 32, 2)
    print(f"The temperature in Fahrenheit: {fahrenheit} °F")  # Alt + 0176
elif unit == "F":
    celsius = round((temp - 32) * 5 / 9, 2)
    print(f"The temperature in Celsius: {celsius} °C")   # Alt + 0176
else:
    print(f"{unit} is not a valid unit")
```

- Prompts the user to enter a temperature unit (`F` or `C`) and a value.
- Converts the temperature to the other unit using `if`, `elif`, and `else`.
- Rounds the result to two decimal places for readability.
- Provides clear output with degree symbols for units.
- Handles invalid input gracefully.
