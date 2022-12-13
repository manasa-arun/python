---
title: "and keyword in python"
description: "The 'and' keyword is one of the keyword out of thirty-five keywords in python"
date: "2022-09-07T12:00:05+09:00"
draft: false
link: "python and keyword"
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
`and, or, not, in` these are the `operator keywords` in python.
variable name doesn't match with these keywords.


## `and` keyword in python:

1. The `and` keyword is one of the keyword out of thirty-five keywords in python.
2. python `and` is a logical operator
3. when we want to compare two different conditions we can use this `and` operator.
4. while comparing both operands are `True` then condition is becomes `True`.

### `and()` keyword Examples:

let's go through some of examples to understand `and()` keyword in python

### Example 1:

```python
a = 25
b = 40
c = 30

print(a>b and c>a)
print(a<=c and b>=c)
print(c==30 and b==20) 
print(a<30 and b>35) 
```
output:

```python
False
True
False
True
```
in this example a,b,c are variables hen we want apply conditions to it or when we ant to compare e can use `and ` keyword like this

check the two conditions and if conditions is satisfied it will give output as `True or False` according to condition.

### Example 2:

```python
if 39 > 39 and 5 < 10:
  print("Both statements are True")
else:
  print("At least one of the statements are False")
```

output:

```python
At least one of the statements are False
```

## Summary
In this tutorial we learnt about Python `and` keyword usage and examples to better understand