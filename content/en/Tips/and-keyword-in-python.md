---
title: "Python 'and' keyword usage,examples"
description: "The 'and' keyword is one of the keyword out of thirty-five keywords in Python"
date: "2022-09-07T12:00:05+09:00"
draft: false
link: "and' keyword"
author: "harika"
---


## Python `and` keyword 

1. The `and` keyword is one of the keyword out of thirty-five keywords in Python.
2. Python `and` is a logical operator
3. when we want to compare two different conditions we can use this `and` operator.
4. while comparing both operands are `True` then condition is becomes `True`.

## Python `and()` keyword Examples:

let's go through some of examples to understand `and()` keyword in Python

### Example 1:

```Python
a = 25
b = 40
c = 30

print(a>b and c>a)
print(a<=c and b>=c)
print(c==30 and b==20) 
print(a<30 and b>35) 
```
output:

```Python
False
True
False
True
```
In this example a,b,c are variables hen we want apply conditions to it or when we ant to compare e can use `and ` keyword like this

check the two conditions and if conditions is satisfied it will give output as `True or False` according to condition.

### Example 2:

```Python
if 39 > 39 and 5 < 10:
  print("Both statements are True")
else:
  print("At least one of the statements are False")
```

output:

```Python
At least one of the statements are False
```

## Summary
In this tutorial we learnt about Python `and` keyword usage with the help of simple examples.
