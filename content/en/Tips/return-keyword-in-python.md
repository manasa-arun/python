---
title: "Python 'return' keyword usage, examples"
description: " The 'return' keyword is one of the keyword out of thirty-five keywords in Python"
date: "2022-09-21T02:10:05+09:00"
draft: false
link: "'return'keyword"
author: "harika"
---

## Python `return` keyword 

The `return` keyword is one of the keyword out of thirty-five keywords in Python
The `return ` keyword means provide output as stop, means the programing code can `stop` there and it will not go to the next part of execution

The statement after the `return` statement is not executed. If the return statement is without any expression, then None is returned.

## Python `return` keyword Uses

You can use the `return` statement anywhere in the function, and it will immediately exit the function and return the specified value to the caller


## Python `return` keyword Syntax  

```Python
def fun():
    statements
    .
    .
    return [expression]
```

## Python `return` keyword Examples:

let's go through some of examples to understand `return` keyword in Python

### Example 1:
To find out original value of local variable

```Python
# welcome to Pythonshiksha
# program for return keyword usage

def my_list(num):
    for i in range(num):
        print('local variable i:', i)
        return i

print(my_list(5))
```
output:

```Python
local variable i: 0
0
```
In this program `return` keyword is used so it gives the original value and exists the function, so for loop iterated only once and give output only one local variable.

### Example 2:
To find division  of two numbers using `return` keyword

```Python
def mycal():
  return 25/5
  
print(mycal()) 
```
output

```Python
5.0
```
## Example 3:
To find absolute value of numbers

```Python
def absolute_value(x):
  if x < 0:
    return -x
  return x

print(absolute_value(-40))  # Output: 40
print(absolute_value(99))  # Output: 99
```
output:
```Python
40
99
```
Here, the absolute_value function takes a single argument x and returns its absolute value. If the value of x is less than 0, it returns the negation of x, otherwise it returns x itself.


## Summary
In this tutorial we learnt about Python `return` keyword usage with the help of simple examples.