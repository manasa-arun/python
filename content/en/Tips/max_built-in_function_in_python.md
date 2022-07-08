---
title: "max() built-in function in python"
description: "max() built in functions in python"
date: "2022-07-08 T004:30:05+09:00"
draft: false
link: "max() Built-in functions"
author: "harika"
---

## max() function in python:
The `max()` function is one of the built-in function in python. 
The `max()` function can return highest number in the list or dict.
If the values are strings, an alphabetically comparison is done.

# syntax:
```
max(a1,a2,a3,a4...an)
```
a1,a2..an - items present in list to do compare

            (or)
```
max(iterable)            
```
iterable - one or more items in list to do compare

# Example: 1
```
student_marks = (71, 95, 83, 59,88,96)
x = max(student_marks) 
print("highest marks scored:", x)
```
# output:
```
highest marks scored:96
```
# Example: 2

if list is with string type
```
friends_list = ("kathya", "chandu", "meghana")
x = max(friends_list) 
print(x)
```
# output:
```
meghana
```



