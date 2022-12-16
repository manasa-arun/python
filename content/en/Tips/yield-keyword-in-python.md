---
title: "Python 'yield' keyword usage, examples"
description: "The 'yield' keyword is one of the keyword out of thirty-five keywords in python"
date: "2022-09-21T02:10:05+09:00"
draft: false
link: "'yield' keyword"
author: "harika"
---

## python `yield` keyword

1. The `yield` keyword is one of the keyword out of thirty-five keywords in python.

2. The programming code can "continue" to the next stage of execution by using the keyword `yield`, which means to provide output as continue. 

3. The `yield` gives a generator object.


## python `yield` keyword Uses 

1. Using `yield` keyword is highly memory efficient, since the execution happens only when the caller iterates over the object.
2. It is used inside the function, It keeps the states of local variable.
It does not exit the function

## python `Yield` Keyword  Syntax 

```python
def gen_func(x):
    for i in range(x):
        yield i
        
```


## python `yield()` keyword Examples:

let's go through some of examples to understand `yield()` keyword in python

### Example 1:
`yield` keyword can help continue the iteration to get the output.

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

### Example 2:
checking the odd numbers in original list.

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
In this tutorial we learnt about Python `yield` keyword usage with the help of simple examples.