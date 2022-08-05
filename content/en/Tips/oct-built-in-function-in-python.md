---
title: "oct built-in function in python"
description: "oct built in functions in python"
date: "2022-08-05T11:50:05+09:00"
draft: false
link: "oct() Built-in functions"
author: "harika"
---

# oct() in python:
The `oct()` function is a one of the built-in functions in python.
The `oct()` is used for	`Converts a number into an octal`.

Python oct() function is used to get an octal value of an integer number. This method takes an argument and returns an integer converted into an octal string.

It throws an error TypeError if argument type is other than an integer.

## syntax:
```
oct(integer)
```
where,
integer : An integer value which is to be converted into an octal string.
it returns octal value.

# Example:
```
# Binary to Octal
print(oct(0b1))
 
# Hexa to octal
print(oct(0XB))

# Python3 program demonstrating TypeError
print("The Octal representation of 29.5 is " + oct(78.92))
```
output:
```
0o1
0o13

    print("The Octal representation of 29.5 is " + oct(78.92))
TypeError: 'float' object cannot be interpreted as an integer
```

