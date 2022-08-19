---
title: "hasattr built-in function in python"
description: "hasattr built in functions in python"
date: "2022-08-19T11:00:05+09:00"
draft: false
link: "hasattr() Built-in functions"
author: "harika"
---

## hasattr() function in python:
The `hasattr()` function is a one of the built-in functions in python.
`hasattr()` is used for	`Returns True if the specified object has the specified attribute (property/method)`.

# Syntax:
```
hasattr(object, attribute)
```
where,
object 	Required. An object.
attribute 	The name of the attribute you want to check if exists

# Exmple:
```
class employee:
    age = 45
    name = "ccc"

employee = employee()

print("employee's name:", hasattr(employee, "name"))
print("employee's salary:", hasattr(employee, "salary"))
```
# output:
```
employee's name: True
employee's salary: False
```
employee name is exists so it is True.
employee salary is not exists so it is False.


