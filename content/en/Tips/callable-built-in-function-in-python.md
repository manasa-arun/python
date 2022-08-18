---
title: "callable built-in function in python"
description: "callable built in functions in python"
date: "2022-08-18T10:10:05+09:00"
draft: false
link: "callable() Built-in functions"
author: "harika"
---

## callable() function in python:
The `callable()` function is a one of the built-in functions in python.
The `callable()` is used for `Returns True if the specified object is callable, otherwise False`.

# Syntax:
```
callable(object)
```
The callable() method takes only one argument, an object and returns one of the two values:

1.returns True, if the object appears to be callable.
2.returns False, if the object is not callable.

Note: There may be few cases where callable() returns true, but the call to object fails. But if a case returns False, calling object will never succeed

# Exmple:
```
def num1():
  num1 = 5
def num2():
  num2 = 10
my_num = 29
print(callable(num1))
print(num2)
print(callable(my_num))
```
# output:
```
True
<function num2 at 0x2b89e74eaca0>
False
```
here num1 is called so it will  be True.
and my_num is not called so it will be False.



