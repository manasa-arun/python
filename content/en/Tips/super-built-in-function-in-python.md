---
title: "super built-in function in python"
description: "super built in functions in python"
date: "2022-08-15T10:00:05+09:00"
draft: false
link: "python super() Built-in functions"
author: "harika"
---

## str() function in python:

The `str()` function is a one of the built-in functions in python.
`super()` is used for `Returns an object that represents the parent class`.

The super() function is used to give access to methods and properties of a parent or sibling class.

# syntax:
```
super() 
```
No parameters for this function.

# Example:
```
class stu():
    def __init__(self, rno, name, vill):
        self.Rno = rno
        self.name = name
        self.vill = vill
 
# Class freelancer inherits EMP
class Freelance(stu):
    def __init__(rno, name, vill, fn):
        super().__init__(rno, name, vill, fn)
        self.Fname = fn
 
stu_1 = Freelance(self, 20, "abcde", "hyd" , "ABCDE")

print('The RNO is:', stu_1.rno)
print('The Name is:', stu_1.name)
print('The Village is:', stu_1.vill)
print('The Father name is:', stu_1.Fname)
```
output:
```
The RNO is: 20
The Name is: abcde
The Village: hyd
The Father name is: ABCDE
```