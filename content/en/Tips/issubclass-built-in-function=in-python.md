---
title: "issubclass built-in function in python"
description: " issubclass() built in functions in python"
date: "2022-08-22T01:30:05+09:00"
draft: false
link: "issubclass()Built-in functions"
author: "harika"
---

## issubclass() function in python:
The `issubclass()` function is a one of the built-in functions in python.
`issubclass()` is used for `Returns True if a specified class is a subclass of a specified object`.


# Syntax:
```
issubclass(object, subclass)
```
where,
object is Required. An object.
subclass is A class object, or a tuple of class  object.


# Example:
```
class student:
  age = 15

class myObj(student):
  name = "John"
  age = student

x = issubclass(myObj, student)

print(x)
```
# output:
```
True
```