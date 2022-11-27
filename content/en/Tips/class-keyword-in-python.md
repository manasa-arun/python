---
title: "class keyword in python"
description: " The `class` keyword is one of the keyword out of thirty-five keywords in python"
date: "2022-09-20T11:00:05+09:00"
draft: false
link: "python class keywords"
author: "harika"
---

## introduction to keywords:
Keywords are python reserved words.
We cannot use them as constants or variables or any other identifier names.

## list of Thirty-five keywords in python:
we can list out keywords with `help()` 
```python
>>> help ("keywords")

Here is a list of the Python keywords.  Enter any keyword to get more help.

False               class               from                or
None                continue            global              pass
True                def                 if                  raise
and                 del                 import              return
as                  elif                in                  try
assert              else                is                  while
async               except              lambda              with
await               finally             nonlocal            yield
break               for                 not                 
```

you can use `help()` again by passing in the specific keyword that you need more information about. 

## structure  keywords in python:
structure keywords include six of the Thirty-five  total keywords.
 def, class, with, as, pass, lambda keywords are iteration keywords.

## `class` keyword in python:

1. The `class` keyword is one of the keyword out of thirty-five keywords in python.
2. A `class` is a collection of data attributes and methods for a specific 
objects.
3.The `class` keyword is used to define any concept e.g., Complex Number, UI Window, Sparse Matrix and so on which are instantiated using their definitions.


## syntax of `class` keyword in python:

```python
class class_name:
     members
```
After creating the objects, we can involve methods of that class with.(dot)

### `class()` keyword Examples:

let's go through some of examples to understand `class()` keyword in python

### Example 1:

```python
class student:
  def setdata(self,name,rno):
    self._name = name
    self._rno =rno

  def showdata(self):
    print('Name:', self._name)
    print('rno:', self._rno)
  
  s1 = student
  s1.setdata("Aaaa", 25)
  s1.showdata()
```
# output:
```
Name: Aaaa
rno:25
```

## Example 2:

```python
class student:
  name = "aaaa"
  age = 36

p1 = student()

print(p1.name)
```

output:

```python
aaaa
```

## Summary
In this tutorial we learnt about Python `class` keyword usage and examples to better understand.