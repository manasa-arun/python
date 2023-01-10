---
title: "Python 'def' keyword usage, examples"
description: " The 'def' keyword is one of the keyword out of thirty-five keywords in Python"
date: "2022-09-20T11:00:05+09:00"
draft: false
link: "'def' keyword"
author: "harika"
---

## Python `def` keyword 

1. The `def` keyword is one of the keyword out of thirty-five keywords in Python.
2. Python `def `keyword is used to define a function, it is placed before a function name that is provided by the user to create a user-defined function. 

## Python `def` keyword Uses

1. The `def` keyword in Python is used to define a function. 
2. A function is a block of code that can be called (invoked) by name and can take arguments (inputs) and return a value (output).

## Python `def` keyword syntax

```Python
def function name:
    statements
```
with out `def` keyword we can not create a user defined or any function.


## Python `def` keyword Examples:

let's go through some of examples to understand `def` keyword in Python

### Example 1:
To find sum,mul,sub of two numbers

```Python
def add(x,y):
  return x+y

def mul(x,y):
  return x*y

def sub(x,y):
  return x-y
a=10
b=6

print('sum=', add(a,b))
print('mul=', mul(a,b))
print('sub=', sub(a,b))
```
output:

```Python
sum= 16
mul= 60
sub= 4
```
### Example 2: To find GCD

```Python
def main():
    x= int(input("enter x value:"))
    y= int(input("enter y value:"))
    k= gcd(x,y)
    print('gcd =', k)
def gcd(x,y):
    while x!=y:
        if x>y:
            x=x-y
        else:
            y=y-x
    return x;
    
main()
```
output:

```Python
enter x value:18
enter y value:24
gcd = 6
```

## Summary
In this tutorial we learnt about Python `def` keyword usage with the help of simple examples.
