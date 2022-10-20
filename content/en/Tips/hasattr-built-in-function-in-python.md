---
title: "python hasattr() function syntax,usage and examples"
description: "The `hasattr()`function is a one of the built-in functions in python"
date: "2022-08-19T11:00:05+09:00"
draft: false
link: "hasattr() Built-in functions"
author: "harika"
---

## `hasattr()` function in python

1. The `hasattr()` function is a one of the built-in functions in python.
2. The `hasattr()` is used for `Returns True if the specified object has the specified attribute (property/method)`.

## `hasattr()` function Syntax

```python
hasattr(object, attribute)
```
## `hasattr()` function parameters

object 	Required. An object.
attribute 	The name of the attribute you want to check if exists

###  `hasattr()` Example:

```python
class employee:
    age = 45
    name = "ccc"

employee = employee()

print("employee's name:", hasattr(employee, "name"))
print("employee's salary:", hasattr(employee, "salary"))
```
output:

```python
employee's name: True
employee's salary: False
```
employee name is exists so it is True.
employee salary is not exists so it is False.

## Summary
In this tutorial we learnt about Python `hasattr()` function with simple examples.
