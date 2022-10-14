---
title: "iter() function in python"
description: "iter() function syntax,parameters,examples in python"
date: "2022-07-26T11:00:40+09:00"
draft: false
link: "iter() Built-in functions"
author: "harika"
---

## `iter()` function  in python:
The `iter()` function is one of the built-in function in python.
python `iter()` is used for `Returns an iterator object`.


## `iter()` functionsyntax
```pythoon
iter(object, sentinel [optional])
```
## `iter()` function Parameters

The iter() method takes two parameters:

1. object - can be a list, set, tuple, etc.
2. sentinel [optional] - a special value that is used to represent the end of a sequence

## `iter()` function Return Value

The iter() method returns

    iterator object for the given argument until the sentinel character is found
    TypeError for a user-defined object that doesn't implement __iter__(), and __next__() or __getitem()__


### `iter()` function Example:
```python
# list of RAINBOW COLORS
colors = ["VIOLATE", "INDIGO", "BLUE", "GREEN", "YELLOW","ORANGE","RED"]

# iter() with a RAINBOW COLOURS
colors_iter = iter(colors)


print(next(colors_iter), +1)
print(next(colors_iter), +2)
print(next(colors_iter), +3)
print(next(colors_iter), +4)
print(next(colors_iter), +5)
print(next(colors_iter), +6)
print(next(colors_iter), +7)
```
Output
```python
VIOLATE 1
INDIGO 2
BLUE 3
GREEN 4
YELLOW 5
ORANGE 6
RED 7
```
## Summary
In this tutorial we learnt about Python `iter()` function with simple examples