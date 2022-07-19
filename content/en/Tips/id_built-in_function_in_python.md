---
title: "id() function in Python"
description: "In this tutorial we learn how to use id() function in Python"
date: "2022-07-19T10:30:00+00:00"
draft: true
link: "id() built-in functions"
author: "harika"
---

##  python id():
The `id()` function is one of the built-in function in python.
`id()` is used for `Returns the id of an object`.

The syntax for Python id() function is as below –
```
id(object)
```
where,

object = int, float, string, tuple, list, class, function, etc.

The `id()` function in Python returns every object’s “identity.” It returns a `unique integer value `that remains constant throughout the program execution time and cannot be modified or changed.

The ‘id’ in Python stands for Identity. 

Each and every object in Python when stored into the memory is being allocated a unique identification number that helps the Python compiler to perform better and utilize memory efficiently.

Example:
```
a = 31.295
txt = 'python shiksha'
items = ['pencil','pen']


print(id(a))
print(id(31.295))
print(id(txt))
print(id(items))
```
output:
```
27510256
27510256
27295000
19723624
```
here, a and 31.295 are equal in this code so we got same id for this two  values so Python `id()` function assigns them with the equivalent identity number.

Note – The Python `id()` function only takes a single parameter object.
