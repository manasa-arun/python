---
title: "Python 'or' keyword usage, examples"
description: "The 'or' keyword is one of the keyword out of thirty-five keywords in Python"
date: "2022-09-07T12:00:05+09:00"
draft: false
link: "'or' keyword"
author: "harika"
---

## Python `or` keyword 

1. The `or` keyword is one of the keyword out of thirty-five keywords in Python.
2. Python `or` keyword is a logical operator that evaluates to True if either of the operands is True, and False otherwise.

## Python `or` keyword Uses

 The `or ` keyword is used to combine two Boolean expressions and return a single Boolean value.

## Python `or` Keyword Truth Table

|Input 1|       |Input2|            |Output|
|-------|       |------|            |------|
|True	|       | True |            |True  |
|True	|       | False|            |True  |
|False	|       | True |            |True  |
|False	|       | False|            |False |

## Python `or` Truth table can work like this

1. condition 1 is True `or` condition2 is True  then it ill give output as `True`
2. condition 1 is True `or` condition2 is False  then it ill give output as `True`
3. condition 1 is False `or` condition2 is True  then it ill give output as `True`
4. condition 1 is False `or` condition2 is False  then it ill give output as `False`

## Python `or` keyword Examples:

let's go through some of examples to understand `or` keyword in Python

### Example 1:
comparing two boolean expressions and return single  value.

```Python
x = 2
y = 5

result = (x > 0) or (y > 0)
print(result)  # Output: True

result = (x > 5) or (y < 1)
print(result)  # Output: False

result = (x > 1) or (y > 2)
print(result)  # Output: True
```
output:

```Python
True
False
True
```

### Example 2:
In this example a[i]= 'k'  so it will display before k letters in 'Pythonshiksha'.

```Python
i = 0
a = 'Pythonshiksha'
  
while i < len(a):
    if a[i] == 'e' or a[i] == 'k':
        i += 1
        break
  
    print('Current Letter :', a[i])
    i += 1
```
output:

```Python
Current Letter : p
Current Letter : y
Current Letter : t
Current Letter : h
Current Letter : o
Current Letter : n
Current Letter : s
Current Letter : h
Current Letter : i
```

### Example 3: 
if a[i]= 'y' now the output will be like this

```Python
i = 0
a = 'Python shiksha'
  
while i < len(a):
    if a[i] == 'e' or a[i] == 'y':
        i += 1
        break
  
    print('Current Letter :', a[i])
    i += 1
```
output:

```Python
Current Letter : p
`
```
here we got output only p why because now `a[i] is y` so before y letters can display in `Python shiksha` word.

## Summary
In this tutorial we learnt about Python `or` keyword usage with the help of simple examples.