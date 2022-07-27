---
title: "all() function in Python"
description: "In this tutorial we learn how to use all() function in Python"
date: "2022-07-20T03:58:00+00:00"
draft: false
link: "all() built-in functions"
author: "harika"
---
## all():

The `all()` function is one of the built-in functions in python.
`all()` is used for `Returns True if all items in an iterable object are true` otherwise it returns False.

If the iterable object is empty, the all() function also returns True.

# Syntax:
```
all(iterable)
```
where,
iterable -An iterable object (list, tuple, dictionary)

# Example:
```
list = [0, 1, 1]
x = all(list)
print(x)
```
output:
```
False
```
output is False because 0 is have in list.

# Example:2
```
list = [1, 1, 1]
x = all(list)
print(x)
```
output:
```
True
```
output is True because,list have all 1.





