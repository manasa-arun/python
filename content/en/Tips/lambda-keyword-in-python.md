---
title: "lambda keyword in python"
description: " The 'lambda' keyword is one of the keyword out of thirty-five keywords in python"
date: "2022-09-20T11:00:05+09:00"
draft: false
link: "python lambda keywords"
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

## `lambda` keyword in python:

1. The `lambda` keyword is one of the keyword out of thirty-five keywords in python.
2. Small anonymous functions are created with the `lambda` keyword.
3. A lambda function can have one expression but any number of arguments.
4. The result of evaluating the expression is returned. 

## Syntax of `lambda` in python:

```python
lambda arguments: expression
```
anonymous means the function don't have a name for it, these type of functions are created with this `lambda` keyword only.

### `lambda()` keyword Examples:

let's go through some of examples to understand `lambda()` keyword in python

### Example 1:
```python
x = lambda a, b, c : a + b + c

print(x(7, 9, 15)) 
```
output:

```python
31
```
Verify this Example.
Multiple attributes are allowed here, and `lambda` has no function name and an expression that only spans one line.

### Example 2:

```python
first_user = lambda name : print('best python tutorial', name)

# lambda call
first_user('pythonshiksha')
```
output:

```python
best python tutorial pythonshiksha
```

## Summary
In this tutorial we learnt about Python `lambda` keyword usage and examples to better understand.