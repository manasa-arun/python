---
title: "bin() built-in function in python"
description: "bin() built in functions in python"
date: "2022-07-07 T004:30:05+09:00"
draft: false
link: "bin() Built-in functions"
author: "harika"
---
## bin() function in python:

The `bin()` function is one of the built-in functions in python.
The `bin()` function returns the binary version of a specified integer.
The result will always start with the prefix 0b.

# Syntax:
```
bin(n)
```
Parameter Values:
n-Required. An integer

# Example: 1
```
n= bin(31)
print(n)
```
# output:
```
0b11111
```
# Example: 2 bin() with non integer class
```
class Total_Marks:
    TELUGU = 88
    HINDI = 95
    ENGLISH = 79
    MATHS = 99
    SCIENCE = 90
    SOCIAL = 89
    
    def func():
        return TELUGU + HINDI + ENGLISH +SCIENCE+ SOCIAL
        
print('The binary equivalent of Total marks is:', bin(Total_Marks()))
```
# output:
```
TypeError: 'Total_Marks' object cannot be interpreted as an integer
```
# Example: 3 bin() with __index__() for Non-Integer Class:
```
class Total_Marks:
    TELUGU = 88
    HINDI = 95
    ENGLISH = 79
    MATHS = 99
    SCIENCE = 90
    SOCIAL = 89
    
    def __index__(self):
        return self.TELUGU + self.HINDI + self.ENGLISH +self.MATHS +self.SCIENCE+ self.SOCIAL
        
print('The binary equivalent of Total marks is:', bin(Total_Marks()))
```
# output:
```
The binary equivalent of Total marks is: 0b1000011100
```





