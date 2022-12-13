---
title: "else keyword in python"
description: "The 'else' keyword is one of the keyword out of thirty-five keywords in python"
date: "2022-09-09T8:30:05+09:00"
draft: false
link: "python else keyword"
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

## `else` keyword in python

1. The`else` keyword is one of the keyword out of thirty-five keywords in python.

2. The `else` keyword is iteration type of keyword in python.

3. The `else` keyword is a control flow and iteration keyword in python.

4. The `if` block condition is not satisfied then `else` block condition will executes.

## Syntax of `else` keyword in python

```python
if test_condition:
	    statement(s)-true
    else:
	    statement(s)-false
```

### `else()` keyword Examples:

let's go through some of examples to understand `else()` keyword in python

### Example 1:
```python
x = 55
if x > 60:
  print("YES")
else:
  print("NO") 
```
output:

```python
NO
```
In this Example 'x is 55',
`if condition` is '55 is not greater than 60' so the condition is 'not satisfied' and it jump to `else` condition and execute this `else` condition and give output as `NO`.


### Example 2: comparing numbers using `else` keyword

```python
num1 = input("Enter a number: ")
num2 = input("Enter another number:")

# comparing numbers 
if num1> num2:
    print("num1 is small")
else:
    print("num 2 is big")
```
output:

```python
Enter a number: 22
Enter another number:23
num 2 is big
```
here `num1 is 22`, `num2 is 23` so if (22>23)condition is not satisfied then `else` statement can executed as `num2 is big`


## Summary
In this tutorial we learnt about Python `else` keyord usage and examples in detail.




