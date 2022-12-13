---
title: "None keyword in python"
description: "The 'None' keyword is one of the keyword out of thirty-five keywords in python"
date: "2022-09-06T03:25:05+09:00"
draft: false
link: "python None keyword"
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

## `None` keyword in python:

1. The `None` keyword is one of the keyword out of thirty-five keywords in python.
2. `None` is a very curious key word in python why because None data doesn't represent any data in it.

## when do we use `None` keyword in python:

We use None in to Two circumstance's
1.To assign a variable
2.Comparing it with any other variable

### `None()` keyword Examples:

let's go through some of examples to understand `None()` keyword in python

### Example 1: `None` is not a value here is an example

```python
print(None+1)
```
output

```python
TypeError: unsupported operand type(s) for +: 'NoneType' and 'int
```
we will get an Type error so None is not a value here.


### Example 2:

```python
x =None
if x ==None :
    print("Ooops sorry...")
```
output

```python
Ooops sorry...
```
### Example 3:

```python
variable = None
if variable is None:
    print("variable is None")
else:
    print("variable is not None")
```
output:

```python
variable is None
```
You can substitute any integer for variable is to get the output "variable is not None".

## Summary
In this tutorial we learnt about Python `None` keyword usage and examples to better understand.



