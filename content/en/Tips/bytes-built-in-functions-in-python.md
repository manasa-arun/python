---
title: "bytes() function in Python"
description: "bytes() function syntax,parameters,examples in Python"
date: "2022-06-26T07:30:00+00:00"
draft: false
link: "python bytes() built-in function"
author: "harika"
---

## bytes() function in python
1. The `bytes()` is a Built in function in python.

2. Python's `bytes()` function is used to return a bytes object.

## bytes() function syntax
```python
bytes(x, encoding, error) 
```

## bytes() function parameters
`bytes()`can take three parameters

Parameter 	Description
1. x 	        is A source to use when creating the bytes object.

                If it is an integer, an empty bytes object of the specified size will be created.

                If it is a String, make sure you specify the encoding of the source.

2. encoding 	The encoding of the string
3. error 	    Specifies what to do if the encoding fails.

It's a static version of the `bytearray()` function.

It is capable of producing an empty bytes object of the specified size. 

### Example: bytes() function for string

```python
# welcome to Pythonshiksha
string = "hello python world"  
array = bytes(string, 'utf-8')  
print(array)
```
output
```python
b'hello python world'
```
## Summary
In this tutorial we learnt about Python `bytes()` function with simple examples.
