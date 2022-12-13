---
title: "return keyword in python"
description: " The 'return' keyword is one of the keyword out of thirty-five keywords in python"
date: "2022-09-21T02:10:05+09:00"
draft: false
link: "python return keyword"
author: "harika"
---

## introduction to keywords:
Keywords are python reserved words.
We cannot use them as constants or variables or any other identifier names.

## list of Thirty-five keywords in python:
we can list out keywords with `help()` 
```
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

## Returning keywords in python
return, yield keywords re returning keywords in python.

## `return` keyword in python

The `return ` keyword means provide output as stop, means the programing code can `stop` there and it will not go to the next part of execution

The `yield` gives back the actual returned value.
It is used inside the function.
It destroys the states of local variable.
It exits the function.

The statement after the `return` statement is not executed. If the return statement is without any expression, then None is returned.

The `yield` keyword pauses generator function execution and the value of the expression following the yield keyword is returned to the generator's caller.

## Syntax `return` keyword in python

```python
def fun():
    statements
    .
    .
    return [expression]
```

### `return()` keyword Examples:

let's go through some of examples to understand `return()` keyword in python

### Example 1:

```python
# welcome to Pythonshiksha
# program for return keyword usage

def my_list(num):
    for i in range(num):
        print('local variable i:', i)
        return i

print(my_list(5))
```
output:

```python
local variable i: 0
0
```
In this program `return` keyword is used so it gives the original value and exists the function, so for loop iterated only once and give output only one local variable.

### Example 2:

```python
def mycal():
  return 25/5
  
print(mycal()) 
```
output

```python
5.0
```

## Summary
In this tutorial we learnt about Python `return` keyword usage and examples to better understand.