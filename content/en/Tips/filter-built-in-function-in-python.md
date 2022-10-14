---
title: "python filter() function"
description: "filter() function syntax,parameters,examples in python"
date: "2022-08-18T11:10:05+09:00"
draft: false
link: "filter() Built-in functions"
author: "harika"
---

## filter() function in python:
1. The `filter()` function is a one of the built-in functions in python.
2. The `filter()` is used for `Use a filter function to exclude items in an iterable object`.

## `filter()` Syntax
```python
filter(function, iterable)
```
## `filter()` parameters:

The `filter()` function takes two parameters

    function - a function
    iterable - an iterable like sets, lists, tuples etc.

## filter() Return Value:

The filter() function returns an iterator.

Note: You can easily convert iterators to sequences like lists, tuples, strings etc.

### Example:
```python
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]


def skip_numb(number):
    if number % 3 == 0:
          return True  

    return False

skip_numbers_iterator = filter(skip_numb, numbers)

# converting to list
skip_numbers = list(skip_numbers_iterator)
print(skip_numbers)
```
output
```python
[3,6,9]
```

## Summary
In this tutorial we learnt about Python `filter()` function with simple examples.