---
title: "variables in Python"
description: "A `variable` is a name that represents a value stored in the computer's memory."
date: "2023-02-12T11:15:05+09:00"
draft: false
link: "variables and variable creation in Python"
author: "harika"
---

## Introduction to `variables` in python

1. A `variable` is a name that represents a value stored in the computer's memory.
2. programs usually store data in the computer's memory and perform operations on that data through variables.


## How to create a `variables` in python

1. We can create a 'variable' in Python with assignment statement to create a variable and assign a value.
2. To create a variable in Python, you simply give it a name and assign it a value using the assignment operator (=). For example:

num = 25
a = 10

here `num,a` are variable names `25 and 10` is assigned the numbers to that `num and a `variables.

### Example 1:
```python
a=45
b=20.5
c=a+b
print(c)
```
output:
```python
65.5
```
In the above example a,b,c are variables.
We can not use variables without assigning any value to them. 



In Python, variables are `strongly and dynamically typed`.
## strong typing in Python

1. strong typing means that the type of a value can not be changed. 
2. a string containing only become a number digits doesn't become a number without casting notation.
3. Every change of type requires an explicit conversion.

## Example 2:

```python
x = 22
print(x) # Output: 22
x = 28
print(x) # Output: 28
```

## Dynamic typing in Python

1. Dynamic typing means that runtime values have a type,as opposed to static typing where variables have a type.
2. Python is a dynamically typed language, there is no need to declare the type of a variable before using it.
3. That is, a variable's type is determined automatically based on the value assigned to it.

### Example 3: 
```python
x = 22
print(type(x)) # Output: <class 'int'>
x = "india"
print(type(x)) # Output: <class 'str'>
```
`x= 22` is int type variable 
`x = `india`` is a str type variable but we can not declared here why because variables are dynamically typed in python.

### Example 4: 
```python
Var1 = "python shiksha"
print(Var1)
```
output:
```python
python shiksha
```

