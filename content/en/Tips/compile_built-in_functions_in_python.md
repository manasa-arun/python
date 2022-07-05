---
title: "compile built-in function in python"
description: "compile built in functions in python"
date: "2022-07-05 T004:30:05+09:00"
draft: false
link: "compile() Built-in functions"
author: "harika"
---

## compile() function in python:
`compile()` is one of the built-in functions in python.

The `compile()` function returns the specified source as a code object,
ready to be executed.

# Syntax:
```
compile(source, filename, mode, flag, dont_inherit, optimize)
```
# Parameter Values
Parameter 	Description

1. source: Required. The source to compile, can be a String, a Bytes object, or an AST object

2. filename: Required. The name of the file that the source comes from. If the source does not come from a file, you can write whatever you like

3. mode: Required. Legal values:
   eval: if the source is a single expression
   exec: if the source is a block of statements
   single: if the source is a single interactive statement

4. flags: Optional. How to compile the source. Default 0

5. dont-inherit: Optional. How to compile the source. Default False

6. optimize: Optional,Defines the optimization level of the compiler.
 Default -1


## Example: 1
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
# Example: 2
if source code is single expression then we can use `eval()` built-in function in python
```
x = compile('print("welcome")', 'test', 'eval')
eval(x) 
```
# output:
```
welcome
```





