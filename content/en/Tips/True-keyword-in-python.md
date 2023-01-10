---
title: "Python 'True' keyword usage,examples"
description: "The 'True' keyword is one of the keyword out of thirty-five keywords in Python"
date: "2022-09-06T03:25:05+09:00"
draft: false
link: "'True' keyword"
author: "harika"
---

## Python `True` keyword

1. The `True` keyword is one of the keyword out of thirty-five keywords in Python.
2. The result of a comparison operation is the Boolean value `True`.
3. The `True` keyword is equivalent to 1. 

## Python `True` keyword Uses


The `True` keyword can also be used in other contexts, such as in the condition of a while loop or in a comparison operator (e.g., a == True). 
It is a fundamental concept in Python and is used in many different ways.


## Python `True` keyword Syntax

```Python
if condition:
    # This code will be executed only if the condition is True
    # You can put any code you want to run here
```
In the example above, the code in the if block will only be executed if the condition evaluates to True. If the condition evaluates to False, the code in the if block will be skipped and the program will continue with the code after the if statement.


## Python `True` keyword Examples:

let's go through some of examples to understand `True` keyword in Python

### Example 1:
checking the fundamental concepts by comparing both values

```Python
print(4>1)

print(5==5)

print(10<20)

print(not(35 == 47))

print(1 not in [0,2,4,6,8])

print(65 == 65)

print(25 ==25 or 36 == 87)

print(29 == 29 and 10 == 10)
```
output:

```Python
True
True
True
True
True
True
True
True
```

### Example 2:
when list is empty

```Python
# Create a list
my_list = []

# Check if the list is empty
if not my_list:
    print("list is empty")
    # This code will be executed only if the list is empty
    # You can put any code you want to run here

```
output:

```Python
list is empty
```
## Summary
In this tutorial we learnt about Python `True` keyword usage with the help of simple examples.
