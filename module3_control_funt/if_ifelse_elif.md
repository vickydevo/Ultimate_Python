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