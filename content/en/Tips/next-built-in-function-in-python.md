---
title: "next() function in Python"
description: "next() function syntax,parameters,examples in python"
date: "2022-07-27T02:58+09:00"
draft: false
link: "next() built-in functions"
author: "harika"
---

## `next()` function in python
The `next()` function is one of the built-in functions in python.
`next()` is used for `Returns the next item in an iterable`.

## `next()` function Syntax
```python
next(iterator, default)
```
## `next()` Parameters
`next()` function can take two parameters

1. iterator - next() retrieves next item from the iterator
2. default (optional) - this value is returned if the iterator is exhausted (there is no next item)

## `next()` function Return Value

1. The `next()` function returns the next item from the iterator.
   If the iterator is exhausted, it returns the default value passed as an argument.
2. If the default parameter is omitted and the iterator is exhausted, it raises the StopIteration exception.

### `next()` function Exmaple:
```python
mylist = [10, 2.3, 'parrot']

# converting the list to an iterator
mylist_iterator = iter(mylist)
print(mylist_iterator)

# Output: 10
print(next(mylist_iterator))

# Output: 2.3
print(next(mylist_iterator))

# Output: 'parrot'
print(next(mylist_iterator))


# This will raise Error
# iterator is exhausted
print(next(mylist_iterator))
```
output
```python
<list_iterator object at 0x0133F628>
10
2.3
parrot
Traceback (most recent call last):
    print(next(mylist_iterator))
StopIteration
```
## Summary
In this tutorial we learnt about Python `next()` function with simple examples


