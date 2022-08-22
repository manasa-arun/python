---
title: "isinstance built-in function in python"
description: " isinstance() built in functions in python"
date: "2022-08-22T02:00:05+09:00"
draft: false
link: "isinstance()Built-in functions"
author: "harika"
---

## isinstance() function in python:
The `isinstance()` function is a one of the built-in functions in python.
`isinstance()` is used for `Returns True if a specified object is an instance of a specified object`.

if the type parameter is a tuple, this function will return True if the object is one of the types in the tuple.

# syntax:
```
isinstance(object, classinfo)

```
where,
object: An object to be checked.
classinfo: The class name or a tuple of class names.

Return Value:

Returns True if object is an instance of the specified class info, otherwise returns False.

The isinstance() method checks for the built-in class instances.

# Example:
```
student_name = 'aaa'
student_rno= 10

print(isinstance(student_name, str)) # True
print(isinstance(student_name, int)) # False

print(isinstance(student_rno, int))  # True
print(isinstance(student_rno, str))# False

```
# output:
```
True
False
True
False
```
# Example:
```
x = isinstance(9.5, int)
y = isinstance(9.5, float)

print(x)
print(y)
```
# output:
```
False
True
```