---
title: "tuple function in python"
description: "tuple built in functions in python"
date: "2022-07-01T003:30:05+09:00"
draft: false
link: "functions"
author: "harika"
---

## tuple() in python:

The tuple() function is a one of the built in functions in python.
It is used to create a tuple.
Tuple is a immutable sequence type.

syntax:

tuple(itertor)

tuple() Parameters:

iterable​ (optional) - an iterable (list, range, etc.) or an iterator object.

If the iterable is not passed to tuple(), the function returns an empty tuple.

## Example:**
1. To create empty tuple:
```
t1 = tuple()
print('t1 =', t1)
```
**output:**
```
t1 = ()
```

2. To create a tuple from a list:
```
t2 = tuple([22,35,7,9.2])
print('t2 =', t2)
```
**output:**
```
t2 = 22,35,7,9.2
```
3. To crete a tuple from string:
```
t1 = tuple('Python')
print('t1 =',t1)
```
**output:**
```
t1 = ('P', 'y', 't', 'h', 'o', 'n')
```
4. To create a tuple from dictionary:
```
t1 = tuple({1: 'one', 2: 'two' , 3:'three'})
print('t1 =',t1)
```
**output:**
```
t1 = (1,2,3)





