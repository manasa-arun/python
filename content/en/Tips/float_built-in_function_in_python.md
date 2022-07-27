---
title: "float built-in function in python"
description: "float built in functions in python"
date: "2022-07-20T03:30:05+09:00"
draft: false
link: "float() Built-in functions"
author: "harika"
---

## float():
The `float()` function converts the specified value into a floating point number.

# Syntax:
```
float(value)
```
where,
value- A number or a string that can be converted into a floating point number

# Example:

float with `infinity`
```
print(float("infinity"))
```
output:
```
inf
```

# Example:
float with integer
```
print(float("29"))
```
output:
```
29.0
```

# Example:
float with string
```
print(float("python"))
```
output:
```
print(float("python"))
ValueError: could not convert string to float: 'python'
```
it gives error because 'python' is a string not an integer or decimal.
