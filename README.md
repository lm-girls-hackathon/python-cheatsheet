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

|Type|Example|
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
A `for` loop iterates through values in a collection, such as a list.
```py
colors = ["red", "orange", "yellow", "green", "blue"]
for color in colors:
    print(color)
# Prints red, orange, yellow, green, blue
```
The loop variable, `color`, is assigned to each value in the list. First, `color` is equal to `"red"`, then `"orange"`, then `"yellow"`, and so on.
## While Loops
```py
x = 0
while x < 3:
    x = x + 1
    print(x)
# Prints 1, 2, 3
```
A `while` loops repeats a block of code for as long as a condition is `True`.
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
#### Indexing
To access a value in a list, you use its *index*. An index is the position of a value in a list. The first index is 0, the second index is 1, and so on.
```py
colors = ["red", "green", "blue"]
print(colors[0]) # Prints red
print(colors[2]) # Prints blue
```
We can also use indexing to modify lists.
```py
colors = ["red", "green", "blue"]
colors[1] = "white"
print(colors) # Prints ["red", "white", "blue"]
```
