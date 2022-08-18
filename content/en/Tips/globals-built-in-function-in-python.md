---
title: "globals built-in function in python"
description: "globals built in functions in python"
date: "2022-08-18T02:00:05+09:00"
draft: false
link: "globals() Built-in functions"
author: "harika"
---

## globals() function in python:
The `globals()` function is a one of the built-in functions in python.
`globals()` is used for `Returns the current global symbol table as a dictionary`.

Symbol table: A symbol table is a type of data structure that houses all of the program's necessary data.
These include class names, methods, and variable names.

Python's globals() method provides access to the global symbol table, which contains all data pertaining to the program's global scope. 


# syntax:
```
Syntax: globals()
```
Parameters: No parameters required.

# Example: 1
```
name = 'arjun'
print('Before modification:', name)
  
# Calling global()
globals()['name'] = 'arjun reddy'
print('After modification:', name)
```
# output:
```
Before modification: arjun
After modification: arjun reddy
```

# Example: 2
```
num = 20
globals()['num'] = 55
print('The number is:', num)
```
# output:
```
The number is:
```
we can also modify the number with this global function in python