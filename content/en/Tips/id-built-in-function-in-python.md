---
title: "id() function in Python"
description: "id() function syntax,parameters,examples in python"
date: "2022-07-19T10:30:00+09:00"
draft: false
link: "id() built-in functions"
author: "harika"
---

##  `id()` function in python:
1. The `id()` function is one of the built-in function in python.
2. The `id()` is used for `Returns the id of an object`.

## id() function syntax
```python
id(object)
```
## `id()` function parameters

object = int, float, string, tuple, list, class, function, etc.

## `id()` function return value
1. The `id()` function in Python returns every object’s “identity.” 

2. It returns a `unique integer value `that remains constant throughout the program execution time and cannot be modified or changed.

3. The ‘id’ in Python stands for Identity. 

4. Each and every object in Python when stored into the memory is being allocated a unique identification number that helps the Python compiler to perform better and utilize memory efficiently.

### `id()` function Example:
```python
a = 31.295
txt = 'python shiksha'
items = ['pencil','pen']

print(id(a))
print(id(31.295))
print(id(txt))
print(id(items))
```
output:
```python
27510256
27510256
27295000
19723624
```
here, a and 31.295 are equal in this code so we got same id for this two  values so Python `id()` function assigns them with the equivalent identity number.

Note – The Python `id()` function only takes a single parameter object.

## Summary
In this tutorial we learnt about Python `id()` function with simple examples