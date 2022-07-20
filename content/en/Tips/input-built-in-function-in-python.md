---
title: "input() function in Python"
description: "In this tutorial we learn how to use input() function in Python"
date: "2022-07-19T11:00:00+00:00"
draft: true
link: "input() built-in functions"
author: "harika"
---

## input():
The `id()` function is one of the built-in function in python.
`input()` is used for `Allowing user input`.

The input() function takes input from the user and returns it.

## syntax:
```
input([prompt])
```
## input() Parameters

The `input(`) function takes a single optional argument:

prompt (Optional) - a string that is written to standard output (usually screen) without trailing newline

## input() Return Value

The `input() `function reads a line from the input (usually from the user), 

converts the line into a string by removing the trailing newline, and returns it.

If EOF is read, it raises an EOFError exception.


## Example:
```
name = input("Enter best python tutorial name: ")

print(name)
```
output:
```
Enter best python tutorial name: pythonshiksha
pythonshiksha
```

# Example:

Taking two values from user and adding both values

```
num1 = int(input("Please Enter First Number: "))
num2 = int(input("Please Enter Second Number: "))
addition = num1 + num2
  
# printing
print("The sum of the two given numbers is {} ".format(addition))
```
output:
```
Please Enter First Number: 29
Please Enter Second Number: 31
The sum of the two given numbers is 60
```
like this user can use this `input()` built-in function to add numbers, append the values or any other data collection information this function can useful.