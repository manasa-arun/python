---
title: "value keywords in Python"
description: "Python True,False,None keywords in detail"
date: "2022-09-06T03:25:05+09:00"
draft: false
link: "Python value keywords"
author: "harika"
---

# Introduction to keywords:
Keywords are Python reserved words.
We cannot use them as constants or variables or any other identifier names.
we have Thirty-five key words in Python.
In these key words e discussed here only value key words now.

# value key words:
Out of Thirty-five key words only three key words are there in this value key words.
True,False,None this three key words are in value key words.

# True keyword in Python:
The result of a comparison operation is the Boolean value True.
The True keyword is equivalent to 1. 

# Example:
```
print(4>1)
print(5==5)
print(10<20)
```
# output:
```
True
True
True
```
# False keyword in Python:
The result of a comparison operation is the Boolean value False.
The False keyword is equivalent to 0. 

# Example:
```
print(4>6)
print(5==8)
print(10>20)
```
# output:
```
False
False
False
```
Another example for True and False keywords.
# Example:
```
a = 25
b = 40

print(a+b >=50)
print(a>=20 and b>=40)
print(a==10 and b==20) #b is not correct so it is false
print(a!=20 and b!=10)
print(a>30 and b>35) # a is not correct so it is false
```
# output:
```
True
True
False
True
False
```
In this above program `a and b` are compared and the condition is satisfied then it will give output as `True` or else after comparing  condition is not satisfied then it will give output as `False`.

you'll see these keywords written in lowercase ( true and false ), but in Python they are always written in uppercase. (True and False)

# None keyword:
None is a very curious key word in Python why because None data doen't represent any data in it.
None is not a value here is an example
```
print(None+1)
```
# output:
```
TypeError: unsupported operand type(s) for +: 'NoneType' and 'int
```
we will get an Type error so None is not a value here.

# when do we use None:
We use None in to Two circumstance's
1.To assign a variable
2.Comparing it with any other variable

# Example:
```
x =None
if x ==None :
    print("Ooops sorry...")
```
# output:
```
Ooops sorry...
```
# Example:
```
variable = None
if variable is None:
    print("variable is None")
else:
    print("variable is not None")
```
# output:
```
variable is None
```
You can substitute any integer for variable is to get the output "variable is not None." 