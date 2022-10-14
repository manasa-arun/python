---
title: "dict() function in python"
description: "dict() function syntax, parameter,examples in python"
date: "2022-06-29T07:40:05+09:00"
draft: false
link: "python dict() functions "
author: "harika"
---

## dict() function in python

1. The `dict()` is one of the built in functions in python.
This function is used to create a dictionary.

2. Dictionary is an object that stores collection of data in Python,which consists of `key-value` pairs which can be used to store data. 

## dict() function syntax
```python
dict(keys values) 
```
## dict() function parameters
keyword arguments 	Required. As many keyword arguments you like, separated by comma: key = value, key = value ...


## sample dictionary in python
my_dict = {'name':'surya','work':'business','age':'30'}

In this sample dictionary  name,work,age are keys of dictionary.
surya,business,30 are values of dictionary.

### Example 1: To find keys in dictionary

```python
emp_dict= {'harika':'1234','saanvi':'1235','santhosh':'1236'}
print(emp_dict.keys())
```
output

```python
dict_keys(['harika', 'saanvi', 'santhosh'])

```
### Example 2: To find values in dictionary
```python
emp_dict= {'harika':'1234','saanvi':'1235','santhosh':'1236'}
print(emp_dict.values())
```
output:
```python
dict_values(['1234', '1235', '1236'])
```
## Summary
In this tutorial we learnt about Python `dict()` function with simple examples.




