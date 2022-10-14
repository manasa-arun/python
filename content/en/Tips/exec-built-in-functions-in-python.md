---
title: "python `exec()` function"
description: "exec() function syntax,parameters,examples in python"
date: "2022-07-05T05:00:05+09:00"
draft: false
link: "exec() Built-in functions"
author: "harika"
---
## exec() function in python

1. The `exec()` function is a one of the built-in functions in python.
2. The `exec()` function executes the specified Python code.
3. The `exec()` function accepts large blocks of code, unlike the `eval()` function which only accepts a single expression

### `exec()`Syntax
```python
exec(object, globals, locals)
```

### `exec()` Parameter Values
object-	A String, or a code object
globals- Optional. A dictionary containing global parameters
locals 	Optional. A dictionary containing local parameter

### `exec()`Example
if source code is block of statements then we can use `exec()` built-in function in python

```python
x = compile('print("welcome to")\nprint("python shiksha")', 'test', 'exec')
exec(x) 
```
output
```python
welcome to
python shiksha
```

## Summary
In this tutorial we learnt about Python `exec()` function with simple examples.


