---
title: "hash built-in function in python"
description: "hash built in functions in python"
date: "2022-08-17T10:00:05+09:00"
draft: false
link: "pyhton hash() Built-in functions"
author: "harika"
---

## hash() function in python:
The `hash()` function is a one of the built-in functions in python.
`hash()` is used for `Returns the hash value`of a specified object.

# Syntax :
```
hash(obj)
```
where,
obj : The object which we need to convert into hash.

python hash() Returns :
Returns the hashed value if possible. 

# Example:
```
int_val = 10
str_val = 'pyhthonshiksha'
flt_val = 32.9
 
# Printing the hash values.
print("The integer hash value is : " + str(hash(int_val)))
print("The string hash value is : " + str(hash(str_val)))
print("The float hash value is : " + str(hash(flt_val)))
```
The integer hash value is : 10
The string hash value is : -635771123
The float hash value is : 214741844
```
Notice Integer value doesn't change in this output.