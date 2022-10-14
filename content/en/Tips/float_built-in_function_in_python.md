---
title: "python float()function "
description: "float() function syntax,parameters,examples in python"
date: "2022-07-20T03:30:05+09:00"
draft: false
link: "float() Built-in functions"
author: "harika"
---

## float() function in python
The `float()` function converts the specified value into a floating point number.

## `float()`Syntax
```python
float(value)
```
##  `float()` parameters
 `float()` can take only one parameter
value- A number or a string that can be converted into a floating point number

### `float()` Example: python `float()` function with infinity
```python
print(float("infinity"))
```
output
```
inf
```

### `float()` Example: python `float()` with integer
```python
print(float("29"))
```
output
```python
29.0
```

### `float()` Example: python `float()` with string
```python
print(float("python"))
```
output
```python
print(float("python"))
ValueError: could not convert string to float: 'python'
```
it gives error because 'python' is a string not an integer or decimal.

## Summary
In this tutorial we learnt about Python `float()` function with simple examples.
