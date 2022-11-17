---
title: "if keyword in python"
description: "The`if` keyword is one of the keyword out of thirty-five keywords in python"
date: "2022-09-09T8:30:05+09:00"
draft: false
link: "python if keyword"
author: "harika"
---

## introduction to keywords:

`Keywords` are python reserved words.
We cannot use them as constants or variables or any other identifier names.
we have Thirty-five keywords in python.

## list of the Python keywords:

False               class               from                or
None                continue            global              pass
True                def                 if                  raise
and                 del                 import              return
as                  elif                in                  try
assert              else                is                  while
async               except              lambda              with
await               finally             nonlocal            yield
break               for                 not  


## `if` keyword in python

1. The `if ` keyword is a control flow and conditional type of keyword in python. 

2. The `if` keyword is one of the keyword out of thirty-five keywords in python.

3. we can only run a block of code if a condition is True by using the `if` keyword to create conditional statements (also known as if statements).
To run code if the condition is False, use the `else` keyword.

## `if` syntax in python:

```python

if condition:
    statements # indent is a must
```

### `if()` keyword Examples:

let's go through some of examples to understand `if()` keyword in python


### Example 1: for 'if' keyword

```python
even_numbers = [0,2,4,6,8]

if 4 in even_numbers:
    print("it is an even number")
else:
    print("it is a odd number")
```
output:

```python
it is an even number
```
In this example 1 '4' is an even number so if condition satisfied then if condition block executed and give out put as 'it is an even number'

### Example 2:

```python
x=10
if x>0:
    print("it is positive number")
```

output:

```python
it is a positive number
```
## Summary
In this tutorial we learnt about Python `if` keyword usage and examples to better understand