---
title: "python int() function syntax,usage and examples"
description: "The 'int()' function is one of the built-in function in python."
date: "2022-06-29T07:40:05+09:00"
draft: false
link: "int() built-in functions"
author: "harika"
---

## `int()` function in python

1. The `int()` function is one of the built-in function in python.
2. Python `int()` function converts the specified value into an integer number, that means if the number is in float,decimal numbers can convert in to integers with this `int()` function.

## `int()` Function Syntax 

```python
   Syntax: int(x, base)
```
## Python `int()` Function parameters

x [optional]: string representation of integer value, defaults to 0, if no value provided.
base [optional]: (integer value) base of the number.

## `int()` function return value

Returns: Return decimal (base-10) representation of x

### `int()` function Examples:

let's go through couple of examples to understand `int()` function in python

### Example 1:

```python
x = 12.5
y = 3.9

a= int(x)
b =int(y)
print(x, y)
```
output:

```python
12 3
```

### Example 2:

```python
x = int("66")

print(x)
```
output:

```
66
```

## Summary
In this tutorial we learnt about Python `int()` function with simple examples
