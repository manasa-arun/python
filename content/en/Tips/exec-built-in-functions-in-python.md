
---
title: "exec built-in function in python"
description: "exec built in functions in python"
date: "2022-07-05T05:00:05+09:00"
draft: false
link: "exec() Built-in functions"
author: "harika"
---
## exec() function in python:

The `exec()` function is a one of the built-in functions in python.
The `exec()` function executes the specified Python code.
The `exec()` function accepts large blocks of code, unlike the `eval()` function which only accepts a single expression

# Syntax:
```
exec(object, globals, locals)
```

# Parameter Values:
object-	A String, or a code object
globals- Optional. A dictionary containing global parameters
locals 	Optional. A dictionary containing local parameter

## Example: 
if source code is block of statements then we can use `exec()` built-in function in python
```
x = compile('print("welcome to")\nprint("pythonshiksha")', 'test', 'exec')
exec(x) 
```
# output:
```
welcome to
pythonshiksha
```