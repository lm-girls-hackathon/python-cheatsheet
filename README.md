# Python Cheatsheet
## Variables
Variables are declared in Python using the variable name and value. You do not need to specify the type.
#### Examples
```py
x = 5
name = "Tommy"
pi = 3.1415
```
#### Variable Types

| Type| Example |
|-|-|
|`bool`|`x = True`|
| `int`|`x = 1`|
| `float`|`e = 2.71828`|
|`str`|`name = "Tommy"`|
|`list`|`numbers = [1, 11, 21, 1121]`|

## Print Statements
```py
name = "Andrew"
print(name) # Prints Andrew
```

#### Explanation
You can print out variables or statements using the `print` function. Simply enter in a variable or value as an argument, and it will output on the console.

## Indentation
Indentation in Python is very important :(.
## If Statements
```py
x = 1
if x == 3:
    print("x is equal to 3")
elif x == 5:
    print("x is equal to 5")
else:
    print("x was not equal to 3 and not equal to 5")
# Prints x was not equal to 3 and not equal to 5
```
If statements allow you to run certain lines of code based on specific conditions. `if` is the keyword to start the block. If the condition is true, the code in the block is executed. `elif` statements are checked if the preceding checks were `False`. If nothing has executed by the time the `else` is reached, the code in the `else` block runs.

## For Loops

## While Loops

## Lists
```py
# Creating an empty list
numbers = [ ]
# Creating a list with initial elements
numbers = [1, 1, 2, 3, 5]
```
The elements in a list can be any type.
```py
potpourri = [1, False, "Carla", 2.718]
```
