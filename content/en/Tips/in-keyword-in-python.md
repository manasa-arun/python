---
title: "Python 'in' keyword usage, examples"
description: "The 'in' keyword is one of the keyword out of thirty-five keywords in python"
date: "2022-09-07T12:00:05+09:00"
draft: false
link: "'in' keyword"
author: "harika"
---

## `in` keyword in python

1. The `in` keyword is one of the keyword out of thirty-five keywords in python.
2. The `in` is a membership operator in python.

## Python `in` keyword Uses

1. The `in` keyword is used to check if a value is present in a sequence (list, range, string etc.).
2. The`in` keyword is also used to iterate through a sequence in a for loop:

## Python `in` keyword Examples

let's go through some of examples to understand `in` keyword in python

### Example 1:

In this example `c` is not there in `vowels` so output is `no`

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

### Example 2:

Here we are checking if  the word `pythonshiksha` contains `f` letter.

As there is no `f`, it will display all the letters in it.


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


### Example 3:

Here `i is h` now so `h` before letters are displayed from  `pythonshiksha` (p,y,t) word.


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

## Summary

In this tutorial we learnt about Python `in` keyword usage with the help of simple examples.