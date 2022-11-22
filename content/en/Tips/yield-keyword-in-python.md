---
title: "yield keyword in python"
description: " The `yield` keyword is one of the keyword out of thirty-five keywords in python"
date: "2022-09-21T02:10:05+09:00"
draft: false
link: "python yield keyword"
author: "harika"
---

# introduction to keywords:
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
`return, yield` keywords re returning keywords in python.

## `yield` keyword in python

1. The `yield` keyword is one of the keyword out of thirty-five keywords in python.

The `yield ` keyword means provide output as continue, means the programing code can `continue` to the next part of execution.

The `yield` gives a generator object.
It is used inside the function.
It keeps the states of local variable.
I does not exit the function


### `yield()` keyword Examples:

let's go through some of examples to understand `yield()` keyword in python

### Example 1:

```python
# welcome to Pythonshiksha
# program for yield keyword 

def my_list(num):
    for i in range(num):
        print('local variable i:', i)
        yield i

print(my_list(5))
print(list(my_list(5)))
```

output:

```python
<generator object my_list at 0x006C4680>
local variable i: 0
local variable i: 1
local variable i: 2
local variable i: 3
local variable i: 4
[0, 1, 2, 3, 4]
```
`yield` keyword can help continue the iteration to get the output.

### Example 2:

```python
def print_odd(my_list):
    for i in my_list:
        if i % 2 == 1:
            yield i
 
# initializing list
my_list = [31, 40, 59, 66, 27]
print("The original list is : " + str(my_list))
print("The odd numbers in list are : ", end=" ")
for j in print_odd(my_list):
    print(j, end=" ")
```

output

```python
The original list is : [31, 40, 59, 66, 27]
The odd numbers in list are :  31 59 27
```

## Summary
In this tutorial we learnt about Python `yield` keyword usage and examples to better understand