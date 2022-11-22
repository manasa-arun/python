---
title: "in keyword in python"
description: "The `in` keyword is one of the keyword out of thirty-five keywords in python""
date: "2022-09-07T12:00:05+09:00"
draft: false
link: "python in keyword"
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


## operator keywords in python:
Operator keywords include four of the Thirty-five  total keywords. 
`and, or, not, in`  these are the `operator keywords` in python.
variable name doesn't match with these keywords.

## `in` keyword in python:

1. The `in` keyword is one of the keyword out of thirty-five keywords in python.
2. The `in` is a membership operator in python.

## The `in` keyword has two purposes:

1. The `in` keyword is used to check if a value is present in a sequence (list, range, string etc.).

2. The`in` keyword is also used to iterate through a sequence in a for loop:

### `in()` keyword Examples:

let's go through some of examples to understand `in()` keyword in python

### Example 1:

```python
vowels = ["a","e","i","o","u"]

if "c" in vowels:
    print("yes")
else:
    print("no")
```
output:

```python
no
```
In this example 'c' is not there in 'vowels' so output is 'no'

### Example 2:

```python
best_tutorial = "pythonshiksha"
 
# Iterating through the string
for i in best_tutorial:
     # break the loop
    if i == 'f':
        break
     
    print(i)
```
output:

```python
p
y
t
h
o
n
s
h
i
k
s
h
a
```
here `i is f` now in `pythonshiksha` word`'f` letter is not there so it will display all the letters in it.


### Example 3: if `i = h `

```python
best_tutorial = "pythonshiksha"
 
# Iterating through the string
for i in best_tutorial:
     # break the loop
    if i == 'h':
        break
     
    print(i)
```

output:

```python
p
y
t
```
here `i is h` now so `h` before letters are displayed from  `pythonshiksha` (p,y,t) word.

## Summary
In this tutorial we learnt about Python `in` keyword usage and examples to better understand