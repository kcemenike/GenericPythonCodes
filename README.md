# GenericPythonCodes
This is just a repo of generic python codes, mostly housed in iPython notebooks.

# Prerequisite(s)
I shall do as much as I can to insert all required modules as import statements on the first line of the notebook. They are mostly popularly known modules - if you get any error while trying to run this first line, just run:
pip install [module] without the square braces

## Understanding Underscores in Python
The underscore is a really powerful tool. You may have seen it in your introduction to Object Oriented Programming (OOP) in Python (def __init__(self): or something like this) or in other applications, but this notebook tries to descrive a few uses of the underscore character in Python
1. Interpreter
2. Variable<br>
  a. Ignore Element in iterable<br>
  b. Ignore multiple elements in iterable<br>
  c. Loop variable / List comprehensions / Lambda functions etc<br>
3. BaseX number representation<br>
4. In OOP (object oriented programming)<br>
  a. Single leading underscore e.g. \_var<br>
  b. Single Trailing and Double trailing Underscore e.g. var\_ and var\_\_<br>
  c. Double leading underscore e.g. \_\_var<br>
  d. Reverse data mangling<br>
5. Double Leading and Trailing Underscores e.g. \_\_var\_\_

## Random Letter and Random String Generator using random.choice
This code generates a random letter and a random string of length n

### 3 ways to reverse a list
1. Using reverse()
2. Using reversed()
3. Using list slicing [::-1]
