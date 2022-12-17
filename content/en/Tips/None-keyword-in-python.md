---
title: "Python 'none' keyword usage, examples"
description: "The 'None' keyword is one of the keyword out of thirty-five keywords in python"
date: "2022-09-06T03:25:05+09:00"
draft: false
link: "'None' keyword"
author: "harika"
---


## python `None` keyword

1. The `None` keyword is one of the keyword out of thirty-five keywords in python.
2. `None` is a very curious key word in python why because None data doesn't represent any data in it.

## python `None` keyword Uses

We use None in to Two circumstance's
1.To assign a variable
2.Comparing it with any other variable

## python `None()` keyword Examples:

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


### Example 2: when `none` have a value

```python
x =None
if x ==None :
    print("Ooops sorry...")
```
output

```python
Ooops sorry...
```
### Example 3: when variable is none

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
In this tutorial we learnt about Python `none` keyword usage with the help of simple examples.


