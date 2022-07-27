---
title: "hex() function in Python"
description: "In this tutorial we learn how to use hex() function in Python"
date: "2022-07-19T11:30:00+09:00"
draft: false
link: "hex() built-in functions"
author: "harika"
---

## hex():
The `hex()` function is one of the built-in functions in python.
`hex()` is used for	`Converts a number into a hexadecimal value`.
The returned string always starts with the prefix 0x.

# Syntax:
```
hex(number)
```
where,
number is `An Integer`

# Example:
```
number = 2022
print(number, 'in hex =', hex(number))

number = 0
print(number, 'in hex =', hex(number))

number = -29
print(number, 'in hex =', hex(number))

returnType = type(hex(number))
print('Return type from hex() is', returnType)
```
output:
```
2022 in hex = 0x7e6
0 in hex = 0x0
-29 in hex = -0x1d
Return type from hex() is <class 'str'>
```
If you need to find a hexadecimal representation of a float, you need to use `float.hex()` method.

# Example:
```
number = 2.5
print(number, 'in hex =', float.hex(number))
```
output:
```
2.5 in hex = 0x1.4000000000000p+1
```
2.5 hexadecimal value is 0x1.4000000000000p+1
-2.5 hexadecimal value is -0x1.4000000000000p+1 difference is only `-` value will be same 


