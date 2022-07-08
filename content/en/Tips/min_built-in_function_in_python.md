---
title: "min() built-in function in python"
description: "min() built in functions in python"
date: "2022-07-08 T004:30:05+09:00"
draft: false
link: "min() Built-in functions"
author: "harika"
---

## min() function in python:
The `min()` function is one of the built-in function in python. 
The `min()` function can return smallest number in the list or dict.
If the values are strings, an alphabetically comparison is done.

# syntax:
```
min(a1,a2,a3,a4...an)
```
a1,a2..an - items present in list to do compare

            (or)
```
min(iterable)            
```
iterable - one or more items in list to do compare

# Example: 1
```
student_marks = (71, 95, 83, 59,88,96)
x = min(student_marks) 
print("lowest marks scored:", x)
```
# output:
```
lowest marks scored: 59
```
# Example: 2

if list is with string type
```
friends_list = ("kathya", "chandu", "meghana","nani")
x = min(friends_list) 
print(x)
```
# output:
```
nani
```
# Example:3
```
list = [1.9, 2.24,9.9,6.8,7.05]
min_value = min(list)
print(min_value)
```
# output:
```
1.9
```