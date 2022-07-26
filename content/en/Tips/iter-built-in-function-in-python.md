---
title: "iter built-in function in python"
description: "iter built in functions in python"
date: "2022-07-26 T011:00:40+09:00"
draft: true
link: "iter() Built-in functions"
author: "harika"
---

## iter() in python:
The `iter()` function is one of the built-in function in python.
python `iter()` is used for `Returns an iterator object`.


# syntax:
```
iter(object, sentinel [optional])
```
iter() Parameters:

The iter() method takes two parameters:

    object - can be a list, set, tuple, etc.
    sentinel [optional] - a special value that is used to represent the end of a sequence

iter() Return Value

The iter() method returns:

    iterator object for the given argument until the sentinel character is found
    TypeError for a user-defined object that doesn't implement __iter__(), and __next__() or __getitem()__


## Example:
```
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
Output:
```
VIOLATE 1
INDIGO 2
BLUE 3
GREEN 4
YELLOW 5
ORANGE 6
RED 7
```