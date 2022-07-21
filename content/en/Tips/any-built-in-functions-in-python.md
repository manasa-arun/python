---
title: "any() function in Python"
description: "In this tutorial we learn how to use any() function in Python"
date: "2022-07-21T10:00:00+00:00"
draft: true
link: "any() built-in functions"
author: "harika"
---

## any():
The `any()` function is one of the built-in functions in python.
Python any() function returns True if any of the elements of a given iterable( List, Dictionary, Tuple, set, etc) are True else it returns False. 

# Syntax: 
```
any(iterable)
```
where, Iterable: It is an iterable object such as a dictionary, tuple, list, set, etc.                 

Returns: Python any() function returns true if any of the items is True.

# Example: any() function with list.
```
# All elements of list are false
l = [ 0, 0, False]
print(any( l ))
 
# Some elements of list are
# true while others are false
l = [ 0, 0, 9, 12, False]
print(any( l ))
 
# Empty List
l = []
print(any( l ))
```
output:
```
True
False
True
False
```
like this, In this list place we can use dictionaries,strings,tuples,sets for all these methods any() function can give output either true or false.

if the particular element is in that list or dictionary it will give TRUE,if there is no element in that it will give FALSE.

# Example: any() function ith strings
```
# Non-Empty String
s = "python!"
print(any(s))
 
# Non-Empty String
s = "111"
print(any(s))
 
# Empty string
s = ""
print(any(s))
```
output:
```
True
True
False
```
# Example: Check if any element in list satisfies a condition

```
# initializing list
my_list = [33,21,29,8,39.80]
 
# printing list
print("The original list : " + str(my_list))
 
# Check if any element in list satisfies a condition
# Using any()
res1 = any(ele > 80 for ele in my_list)
res2 = any(ele < 10 for ele in my_list)
 
# Printing result
print("Does any element satisfy specified condition ? : " + str(res1))
print("Does any element satisfy specified condition ? : " + str(res2))
```
output:
```
The original list : [33, 21, 29, 8, 39.8]
Does any element satisfy specified condition ? : False
Does any element satisfy specified condition ? : True
```



