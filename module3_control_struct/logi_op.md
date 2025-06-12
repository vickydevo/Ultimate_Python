# Logical Operators in Python

Logical operators allow you to evaluate multiple conditions in your code. The main logical operators in Python are `and`, `or`, and `not`.

## `and` Operator

Returns `True` if **both** conditions are true.

```python
x = 5
if x > 2 and x < 10:
    print("x is between 2 and 10")
```

## `or` Operator

Returns `True` if **at least one** condition is true.

```python
x = 5
if x < 2 or x > 3:
    print("x is less than 2 or greater than 3")
```

## `not` Operator

Reverses the result of a condition.

```python
x = 5
if not x == 10:
    print("x is not 10")
```

Use these operators to combine and evaluate multiple conditions in your programs.

## Practical Examples

### Using `or` Operator

```python
temp = -5
is_raining = False

if temp > 35 or temp < 0 or is_raining:
    print("The outdoor event is cancelled")
else:
    print("The outdoor event is still scheduled")
```

### Using `and` and `not` Operators

```python
temp = 222
is_sunny = False

if temp >= 25 and is_sunny:
    print("It is HOT outside")
    print("It is SUNNY")
elif temp <= 0 and is_sunny:
    print("It is COLD outside")
    print("It is SUNNY")
elif 25 >= temp > 0 and is_sunny:
    print("It is WARM outside")
    print("It is SUNNY")
elif temp >= 25 and not is_sunny:
    print("It is HOT outside")
    print("It is CLOUD")
elif temp <= 0 and not is_sunny:
    print("It is COLD outside")
    print("It is CLOUD")
elif 25 >= temp > 0 and not is_sunny:
    print("It is WARM outside")
    print("It is CLOUD")
```