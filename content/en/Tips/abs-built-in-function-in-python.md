---
title: "abs built-in function in python"
description: "abs built-in functions in python"
date: "2022-07-07T03:40:05+09:00"
draft: false
link: "abs() Built-in functions"
author: "harika"
---

## abs() function in python:
The `abs()` function is a one of the built-in functions in python.
`abs()` is used for `Returns the absolute value of a number`.

Syntax: 

```
abs(number)
```
parameters:
number: Can be an integer, a floating-point number or a complex number

If the argument is an integer or floating-point number, abs() returns the absolute value in integer or float.

In the case of a complex number, abs() returns only the magnitude part and that can also be a floating-point number.

# how it works abs() in python:

1.positive numbers are not effective in this function.

2.if the number is negative that number can multiply with `-1` and returns positive number only.

# Example:1
if the number is float number with negative it will returns positive number like this
```
float = -36.75
print('Absolute value of float is:', abs(float))
```
# output:
```
Absolute value of float is: 36.75
```
# example: 2
if the number is integer  with negative it will returns positive number like this
```
int = -29
print('Absolute value of integer is:', abs(int))
```
# output:
```
Absolute value of integer is:29
```
# example: 3
if the number is complex number `abs()` returns only the magnitude part and that can also be a floating-point number.

```
complex = (4 - 8j)
print('Absolute value or Magnitude of complex is:', abs(complex))
```
# output:
```
Absolute value or Magnitude of complex is: 8.94427190999916
```





