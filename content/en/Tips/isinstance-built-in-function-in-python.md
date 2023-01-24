---
title: "Python isinstance() function syntax,usage and examples "
description: "The 'isinstance()' function is a one of the built-in functions in Python"
date: "2022-08-22T02:00:05+09:00"
draft: false
link: "isinstance()Built-in functions"
author: "harika"
---

## `isinstance()` function in Python

1. The `isinstance()` function is a one of the built-in functions in Python.
2. `isinstance()` is used for `Returns True if a specified object is an instance of a specified object`.

##  `isinstance()` function syntax

```Python
isinstance(object, classinfo)
```
##  `isinstance()` function parameters
object: An object to be checked.
classinfo: The class name or a tuple of class names.


##  `isinstance()` function Return Value

Returns True if object is an instance of the specified class info, otherwise returns False.

The `isinstance()` method checks for the built-in class instances.

if the type parameter is a tuple, this function will return True if the object is one of the types in the tuple.

## `inistance()` function Examples:

let's go through couple of examples to understand `inistance()` function in Python

### `isinstance()` function Example 1

```Python
student_name = 'aaa'
student_rno= 10

print(isinstance(student_name, str)) # True
print(isinstance(student_name, int)) # False

print(isinstance(student_rno, int))  # True
print(isinstance(student_rno, str))# False
```
output:

```Python
True
False
True
False
```
### `inistance() `Example 2:

```Python
x = isinstance(9.5, int)
y = isinstance(9.5, float)

print(x)
print(y)
```
output:

```Python
False
True
```

## Summary
In this tutorial we learnt about Python `isinstance()` function with simple examples