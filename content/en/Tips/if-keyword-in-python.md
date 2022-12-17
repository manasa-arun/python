---
title: "Python 'if' keyword usage, examples"
description: "The 'if' keyword is one of the keyword out of thirty-five keywords in python"
date: "2022-09-09T8:30:05+09:00"
draft: false
link: "'if' keyword"
author: "harika"
---

## python `if` keyword 

1. The `if` keyword is one of the keyword out of thirty-five keywords in python.
2.  The `if ` keyword is a control flow and conditional type of keyword in python. 
3. we can only run a block of code if a condition is True by using the `if` keyword to create conditional statements (also known as if statements).
To run code if the condition is False, use the `else` keyword.
4. You can also use the `elif ` keyword to specify additional conditions that should be checked if the previous condition was not met:

## python `if` keyword Uses

In Python, the `if` keyword is used to specify a conditional statement. A conditional statement is a block of code that is executed only if a certain condition is met.

## python `if` syntax 

```python

if condition:
    statements # indent is a must
```

## python `if` keyword Examples:

let's go through some of examples to understand `if` keyword in python


### Example 1: using `if` keyword to find type of numbers

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
In this example 1 `4` is an even number so if condition satisfied then if condition block executed and give out put as `it is an even number`

### Example 2:
To get positive number

```python
x=10
if x>0:
    print("it is positive number")
```
output:

```python
it is a positive number
```
### Example 3:
using `elif` keyword with `if` keyword

```python
x = 10

if x > 15:
    print("x is greater than 15")
elif x < 25:
    print("x is less than 25")
else:
    print("x is equal to 5")
```
output

```python
x is less than 25
```
In this example, the first condition `x > 15 is evaluated as False`, so the second condition `x < 25 is checked`. This condition is evaluated as `True`, so the block of code inside the `elif` statement is executed.

## Summary
In this tutorial we learnt about Python `if` keyword usage with the help of simple examples.


