---
title: "or keyword in python"
description: "The 'or' keyword is one of the keyword out of thirty-five keywords in python"
date: "2022-09-07T12:00:05+09:00"
draft: false
link: "python or keyword"
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
`and, or, not, in`these are the `operator keywords` in python.
variable name doesn't match with these keywords.


## `or` keyword in python:

1. The `or` keyword is one of the keyword out of thirty-five keywords in python.
2. python `or` keyword is a logical operator

## Python `OR` Keyword Truth Table

Input 1  	  Input2	         Output
True	      True	         True
True	      False	         True
False	      True	         True
False	      False	         False

## `or` Truth table can work like this if :

1. condition 1 is True `or` condition2 is True  then it ill give output as `True`
2. condition 1 is True `or` condition2 is False  then it ill give output as `True`
3. condition 1 is False `or` condition2 is True  then it ill give output as `True`
4. condition 1 is False `or` condition2 is False  then it ill give output as `False`

### `or()` keyword Examples:

let's go through some of examples to understand `or()` keyword in python

### Example 1:

```python
i = 0
a = 'pythonshiksha'
  
while i < len(a):
    if a[i] == 'e' or a[i] == 'k':
        i += 1
        break
  
    print('Current Letter :', a[i])
    i += 1
```
output:

```python
Current Letter : p
Current Letter : y
Current Letter : t
Current Letter : h
Current Letter : o
Current Letter : n
Current Letter : s
Current Letter : h
Current Letter : i
```
In this example a[i]= 'k'  so it will display before k letters in 'pythonshiksha'.

### Example 2: if a[i]= 'y' now the output will be like this

```python
i = 0
a = 'python shiksha'
  
while i < len(a):
    if a[i] == 'e' or a[i] == 'y':
        i += 1
        break
  
    print('Current Letter :', a[i])
    i += 1
```
output:

```python
Current Letter : p
`
```
here we got output only p why because now `a[i] is y` so before y letters can display in `python shiksha` word.

## Summary
In this tutorial we learnt about Python `or` keyword usage and examples to better understand
