---
title: "hash() function in python"
description: "hash() function syntax,parameters,examples in python"
date: "2022-08-17T10:00:05+09:00"
draft: false
link: "pyhton hash() Built-in functions"
author: "harika"
---

## `hash()` function in python
The `hash()` function is a one of the built-in functions in python.
`hash()` is used for `Returns the hash value`of a specified object.

## `hash()` function Syntax 
```python
hash(obj)
```
## `hash()` function parameters

obj : The object which we need to convert into hash.

## `hash()` Returns 
Returns the hashed value if possible. 

### `hash()` Example:
```python
int_val = 10
str_val = 'pyhthonshiksha'
flt_val = 32.9
 
# Printing the hash values.
print("The integer hash value is : " + str(hash(int_val)))
print("The string hash value is : " + str(hash(str_val)))
print("The float hash value is : " + str(hash(flt_val)))
```
output
```python
The integer hash value is : 10
The string hash value is : -635771123
The float hash value is : 214741844
```
Notice Integer value doesn't change in this output.

## Summary
In this tutorial we learnt about Python `hash()` function with simple examples.