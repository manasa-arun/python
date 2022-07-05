---
title: "bytes() function in Python"
description: "In this tutorial we learn how to use bytes() function in Python"
date: "2022-06-26T07:30:00+00:00"
draft: false
link: "bytes() built-in functions in python"
author: "harika"
---

## bytes()
The `bytes()` is a Built in function in python.

Python's `bytes()` function is used to return a bytes object.

It's a static version of the `bytearray()` function.

It is capable of producing an empty bytes object of the specified size. 

**Example**
```
string = "hello python world"  
array = bytes(string, 'utf-8')  
print(array)
```
**output:**
```  
b'hello python world'
```