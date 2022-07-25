---
title: "print built-in function in python"
description: "print built in functions in python"
date: "2022-07-25 T011:10:40+09:00"
draft: true
link: "print() Built-in functions"
author: "harika"
---

## print() in python:
The `print()` function is one of the built-in function in python.
`print()` is used for `Prints to the standard output device`.

The print() function prints the specified message to the screen,
The message can be a string, or any other object, the object will be converted into a string before written to the screen.

# syntax:
```
print(object(s)), 
sep=separator, end=end, file=file, flush=flush) )
```
object(s)- Any object, 
and as many as you like. Will be converted to string before printed

sep='separator' - (Optional)
Specify how to separate the objects, if there is more than one. Default is ' '

end='end' (Optional) 
Specify what to print at the end. Default is '\n' (line feed)

file (Optional) 
An object with a write method. Default is sys.stdout

flush (Optional) 
A Boolean, specifying if the output is flushed (True) or buffered (False). Default is False

## Example:1
```
print("welcome to pythonshiksha")
print("easy to learn")
```
output:
```
welcome to pythonshiksha
easy to learn
```
# Example:2
```
print("Hello", "BEST TUTORIAL FOR PYTHON", sep="---")
```
Output:
```
Hello---BEST TUTORIAL FOR PYTHON
```
whatever we can write in print function can display on the screen that is any spelling mistakes in any words or any type of data type also can display on the screen.

# Example:3
```
print("mnbjj,787,9.0,hdhk,hyd")
```
output:
```
mnbjj,787,9.0,hdhk,hyd
```
