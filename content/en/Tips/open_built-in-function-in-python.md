---
title: "open() function in python"
description: "open() function syntax,parameters,examples in python"
date: "2022-08-06T09:00:05+09:00"
draft: false
link: "open() Built-in functions"
author: "harika"
---

## `open()` function in python:
1. The `open()` function is a one of the built-in functions in python.
2. The `open()` is used for `Opens a file and returns a file object`.

## `open()` function Syntax
```python
open(file, mode)
```
## `open()` function parameters
`open()` function can take two parameters.
1. file 	The path and name of the file
2. mode 	A string, define which mode you want to open the file in:


"w" - Write - Opens a file for writing, creates the file if it does not exist

"x" - Create - Creates the specified file, returns an error if the file exist

"r" - Read - Default value. Opens a file for reading, error if the file does not exist

"a" - Append - Opens a file for appending, creates the file if it does not exist


In addition you can specify if the file should be handled as binary or text mode

"t" - Text - Default value. Text mode

"b" - Binary - Binary mode (e.g. images)

# Example:
```python
# opens the file in reading mode
f = open("path_to_file", mode='r')

# opens the file in writing mode 
f = open("path_to_file", mode = 'w')

# opens for writing to the end 
f = open("path_to_file", mode = 'a')
```
## Summary
In this tutorial we learnt about Python `open()` function with simple way
