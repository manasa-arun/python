---
title: "not keyword in python"
description: "The `not` keyword is one of the keyword out of thirty-five keywords in python""
date: "2022-09-07T12:00:05+09:00"
draft: false
link: "python not keyword"
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


## operator keywords in python:
Operator keywords include four of the Thirty-five  total keywords. 
`and, or, not, in`  these are the `operator keywords` in python.
variable name doesn't match with these keywords.

## `not` keyword in python:

1. The `not` keyword is one of the keyword out of thirty-five keywords in python.
2. The `not` keyword is a logical operator.

3. The `not` keyword return value will be `True` if the statement(s) are not `True`, otherwise it will return `False`.
4. The `not` keyword used to reverse the logical state of its operand.

### `not()` keyword Examples:

let's go through some of examples to understand `not()` keyword in python

### Example 1:

```python
a = 5
print(a>1, not a)
```
Output:

```python
True False
```
In this Example 'a is 5' 
a is bigger than 1 so it is 'True'
the condition is 'True' not keyword can give output as 'False'.
so output will be 'True False'

### Example 2:

```python
x =True
print(not x)
```
output:

```python
False
```

## Summary
In this tutorial we learnt about Python `not` keyword usage and examples to better understand