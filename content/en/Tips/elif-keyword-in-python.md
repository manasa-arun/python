---
title: "Python 'elif' keyword usage, examples"
description: "The 'elif' keyword is one of the keyword out of thirty-five keywords in Python"
date: "2022-09-09T8:30:05+09:00"
draft: false
link: "'elif' keyword"
author: "harika"
---

## Python `elif` keyword 

1. The `elif ` keyword is a control flow type of keyword in Python. 

2. The `elif` keyword is one of the keyword out of thirty-five keywords in Python.

3. The `elif` is a term that stands for "else if" and can be used to prevent using too much indentation.

An alternative to switch or case statements common in other languages is an if... elif... elif... sequence.

## Python `elif` keyword Uses

1. The `elif` keyword in Python is used in an if statement to specify additional conditions to be tested. 

2. It is short for `else if,` and is used to check for additional conditions when the first if condition is False.

## Python `elif` keyword syntax 

```Python

elif condition:
    statements 
```

## Python `elif` keyword Examples:

let's go through some of examples to understand `elif` keyword in Python


### Example 1: for `elif` keyword

```Python
a=10
b=6
c= a+b
if c%2 == 0:
    print("c is a even number")
elif c%2 != 0:
    print("c is a odd number")
```
output:
```Python
c is a even number
```
### Example 2:
checking the number positive or negative.

```Python
i = -4
if i > 0:
        print("positive number")
elif i < 0:
    print("negative number")
```
output:

```Python
negative number
```

## Summary
In this tutorial we learnt about Python `elif` keyword usage with the help of simple examples.
