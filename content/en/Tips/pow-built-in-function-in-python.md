---
title: "pow built-in function in python"
description: "pow built in functions in python"
date: "2022-08-06T09:00:05+09:00"
draft: false
link: "pow() Built-in functions"
author: "harika"
---

## pow() function in python:
The `pow()` function is a one of the built-in functions in python.
`pow()` is used for 	`Returns the value of x to the power of y`.

# Syntax:
```
pow(x, y, z)
```
where,
x - is A number, the base
y - is A number, the exponent
z - isOptional. A number, the modulus

## Examaple: pow() with only two parameters
```
x = pow(2, 5) 
print(x)
```
output:
```
32
```
here 2is multiplied by 5 times and return 32.

## Examaple: pow() with only three parameters
```
x = pow(2, 5,3) 
print(x)
```
output:
```
3
```
here 2is multiplied by 5 times and return 32 `(2*2*2*2*2=32)`,
next 32 is divided by `3` that is 3rd parameter and returned 3 (32%3 == 3).

## Example:
```
# Python code to discuss negative
# and non-negative cases
 
# positive x, positive y (x**y)
print("Positive x and positive y : ", end="")
print(pow(5, 2))
 
print("Negative x and positive y : ", end="")
# negative x, positive y (-x**y)
print(pow(-5, 2))
 
print("Positive x and negative y : ", end="")
# positive x, negative y (x**-y)
print(pow(5, -2))
 
print("Negative x and negative y : ", end="")
# negative x, negative y (-x**-y)
print(pow(-5, -2))
```
output:
```
Positive x and positive y : 25
Negative x and positive y : 25
Positive x and negative y : 0.04
Negative x and negative y : 0.04
```
pow returned values list:
if  x and y parameters  then

if x is negative y is negative it returns float value
if x is positive y is negative it returns float value
if x is negative y is positive it returns integer value
if x is positive y is positive it returns integer value

check above example for reference.




