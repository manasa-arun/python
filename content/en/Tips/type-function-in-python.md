---
title: "type function in python"
description: "type built in functions in python"
date: "2022-06-29T11:25:05+09:00"
draft: false
link: "type() built-in function"
author: "harika"
---

## type() in python:

Depending on the inputs supplied, the type() function either returns the type of the object or returns a new type object. 

type() function have two forms:

1.type(name, bases, dict)

parameters used in type:
name - a class name; 
bases - Optional. Specifies the base classes
dict - Optional. Specifies the namespace with the definition for the class (dictionry).

2. type()

single parameter can return a specified type of data.
type of the object, if only one object parameter is passed

**Example:**
```
a = ('TIGER', 'PYTHON', 'BANANA','HYDERABAD')
b = "good morning"
c = 55.8
d = 100

x = type(a)
y = type(b)
z = type(c) 
p = type(d)

print(x,y,z,p)
```
**Output:**
```
<class 'tuple'> <class 'str'> <class 'float'> <class 'int'>
```
In Python, the "type()" function is used to quickly determine what kind of data the user can include in the programme. 