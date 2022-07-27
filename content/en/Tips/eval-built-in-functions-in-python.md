---
title: "eval built-in function in python"
description: "eval built in functions in python"
date: "2022-07-05T05:00:05+09:00"
draft: false
link: "eval() Built-in functions"
author: "harika"
---

## eval() inpython:
The `eval()` function is one of the built-in functions in python.
The `eval()` function evaluates the specified expression, if the expression is a legal Python statement, it will be executed.


# syntax:
eval(expression, globals, locals) 

expression- A String, that will be evaluated as Python code
globals- Optional. A dictionary containing global parameters
locals- Optional. A dictionary containing local parameters


# example:
if source code is single expression then we can use `eval()` built-in function in python
```
x = compile('print("welcome")', 'test', 'eval')
eval(x) 
```
# output:
```
welcome
```


