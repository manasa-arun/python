---
title: "setattr built-in function in python"
description: "setattr built in functions in python"
date: "2022-08-15T006:49:05+09:00"
draft: false
link: "setattr() Built-in functions"
author: "harika"
---

## setattr() function in python:
The `setattr()` function is a one of the built-in functions in python.
`setattr()` is used for `Sets an attribute (property/method) of an object`.

when we want to add a new attribute to an object and set a value to it. 
It returns None to the caller function.

# Syntax:
```
setattr(object, attribute, value)
```
where,
object is Required-An object.
attribute is Required-The name of the attribute you want to set
value is Required-The value you want to give the specified attribute

# Example:
```
class student:
    firstName = 'chandu'
    lastName = 'patel'

std = student()
print('First Name: ', std.firstName)
print('Last Name: ', std.lastName)

setattr(std,'firstName','nandini')
setattr(std,'lastName','reddy')

print('After setting attributes')

print('First Name: ', std.firstName)
print('Last Name: ', std.lastName)
```
output:
```
First Name:  chandu
Last Name:  patel
After setting attributes
First Name:  nandini
Last Name:  reddy
```
here chandu patel is set to nandini reddy.
