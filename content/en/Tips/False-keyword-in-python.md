---
title: "False keyword in python"
description: "The 'False' keyword is one of the keyword out of thirty-five keywords in python"
date: "2022-09-06T03:25:05+09:00"
draft: false
link: "python False keyword"
author: "harika"
---

## Introduction to keywords:
Keywords are python reserved words.
We cannot use them as constants or variables or any other identifier names.
we have Thirty-five key words in python.

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

you can use help() again by passing in the specific keyword that you need more information about. 

## value key words in python
True,False,None this three key words are in value key words in python.

## `False` keyword in python:

1. The `True` keyword is one of the keyword out of thirty-five keywords in python.
2. The result of a comparison operation is the Boolean value `False`.
3. The `False` keyword is equivalent to 0. 


### `False()` keyword Examples:

let's go through some of examples to understand `False()` keyword in python

### Example 1:

```python
print(4>6)
print(5==8)
print(10>20)
```

output:

```python
False
False
False
```

### Example 2:for `True` and `False` keywords

```python
a = 25
b = 40

print(a+b >=50)
print(a>=20 and b>=40)
print(a==10 and b==20) #b is not correct so it is false
print(a!=20 and b!=10)
print(a>30 and b>35) # a is not correct so it is false
```
output

```python
True
True
False
True
False
```
In this above program `a and b` are compared and the condition is satisfied then it will give output as `True` or else after comparing  condition is not satisfied then it will give output as `False`.

you'll see these keywords written in lowercase ( true and false ), but in Python they are always written in uppercase. (True and False)

## Summary
In this tutorial we learnt about Python `False` keyword usage and examples to better understand.

