---
title: "Python 'lambda' keyword usage,examples"
description: " The 'lambda' keyword is one of the keyword out of thirty-five keywords in python"
date: "2022-09-20T11:00:05+09:00"
draft: false
link: "'lambda' keyword"
author: "harika"
---

## Python `lambda` keyword 

1. The `lambda` keyword is one of the keyword out of thirty-five keywords in python.
2. Small anonymous functions are created with the `lambda` keyword.
3. A `lambda` function can have one expression but any number of arguments.
4. The result of evaluating the expression is returned. 

## Python `lambda` keyword Uses

In Python, the `lambda` keyword is used to create small anonymous functions. These functions are often called "lambda functions" or "anonymous functions", and they are often used when you need a simple function for a short period of time.

`Lambda` functions are often used in conjunction with higher-order functions such as `map, filter, and reduce`, which allow you to apply a function to a sequence of data. They are also useful for creating simple functions to be used as event handlers in graphical user interface (GUI) programs.


## Python `lambda` keyword Syntax 

```python
lambda arguments: expression
```
anonymous means the function don't have a name for it, these type of functions are created with this `lambda` keyword only.

## Python `lambda` keyword Examples:

let's go through some of examples to understand `lambda` keyword in python

### Example 1:
Adding numbers using `lambda` keyword 

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
Using `lambda` to print something.

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
In this tutorial we learnt about Python `lambda` keyword usage with the help of simple examples.