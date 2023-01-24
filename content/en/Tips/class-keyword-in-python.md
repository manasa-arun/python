---
title: "Python 'class' keyword usage,examples"
description: " The 'class' keyword is one of the keyword out of thirty-five keywords in Python"
date: "2022-09-20T11:00:05+09:00"
draft: false
link: "'class' keyword"
author: "harika"
---

## Python `class` keyword 

1. The `class` keyword is one of the keyword out of thirty-five keywords in Python.
2. A `class` is a collection of data attributes and methods for a specific 
objects.
3.The `class` keyword is used to define any concept e.g., Complex Number, UI Window, Sparse Matrix and so on which are instantiated using their definitions.

## Python `class` keyword Uses

In Python, the `class` keyword is used to define a new class. A class is a template for creating objects. It defines the attributes and behaviors that objects of the class will have.

## Python `class` keyword syntax 

```Python
class class_name:
     members
```
After creating the objects, we can involve methods of that class with.(dot)

## Python `class` keyword Examples:

let's go through some of examples to understand `class` keyword in Python

### Example 1:

```Python
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
print student name 

```Python
class student:
  name = "aaaa"
  age = 36

p1 = student()
print(p1.name)
```
output:
```Python
aaaa
```
## Summary
In this tutorial we learnt about Python `class` keyword usage with the help of simple examples.
