---
title: "def keyword in python"
description: " The 'def' keyword is one of the keyword out of thirty-five keywords in python"
date: "2022-09-20T11:00:05+09:00"
draft: false
link: "python def keywords"
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

## structure  keywords in python:
structure keywords include six of the Thirty-five  total keywords.
 def, class, with, as, pass, lambda keywords are iteration keywords.

## `def` keyword in python:

1. The `def` keyword is one of the keyword out of thirty-five keywords in python.
2. Python `def `keyword is used to define a function, it is placed before a function name that is provided by the user to create a user-defined function. 

## `def` keyword syntax in python

```python
def function name:
    statements
```
with out `def` keyword we can not create a user defined or any function.


### `def()` keyword Examples:

let's go through some of examples to understand `def()` keyword in python

### Example 1:

```python
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

```python
sum= 16
mul= 60
sub= 4
```
### Example 2: To find GCD

```python
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

```python
enter x value:18
enter y value:24
gcd = 6
```

## Summary
In this tutorial we learnt about Python `def` keyword usage and examples to better understand.