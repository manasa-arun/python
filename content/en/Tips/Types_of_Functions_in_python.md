---
title: "Types of functions in python"
description: "Two important types in functions in python"
date: "2022-06-24T04:15:05+09:00"
draft: false
link: "functions"
author: "harika"
---

## introduction of Functions:
A function is a group statements that exist within a program for the purpose of performing a specific task and it will be executed only when it is called.
## Syantax:
```
>>> def function_name():
	statements
```
## Types of Functions:
Functions are mainly two types in python
1.Predefined functions
2.user defined functions

1.Predefined Functions:
Predefined Functions is also call as `Built-in Functions`.

Python built-in functions are functions that have pre-defined functionality in Python.

The Python interpreter has a number of functions that are always available for use.

These are referred to as Built-in Functions.
Python has several built-in functions, which are listed below: 


1.Python len() Function:

Python has an Built-in function `len()` function for calculating the number of elements inside a list.

This function takes in the string whose length is to be calculated as the argument and this function returns an integer value as the output i.e., the **length** of the string.

## how the len() can work:

1.create a list with any data type
2.find out the `length` of the list with len()
 After this if the list `length`  is `0`then the list is empty.
Otherwise list have something in it.

**example**
```
list1=[]
if len(list1)==0:
    print("list is empty")

```
**output:**
```
list is empty
```
we successfully checked the list is empty with `len()` but this is not recommended by PEP8.

## 2.bool()

Python bool() function is used to return or convert a value to a Boolean value i.e., True or False, using the standard truth testing procedure.

```
bool([])
```
**output**
```
false
```
one more
```
bool([none])
```
**output**
```
true
```

## 3. abs()
The `abs()` function in Python is used to return the absolute value of a number.

It only accepts one argument, a number whose absolute value should be returned.

An integer or a floating-point number can be used as the argument.

If the argument is a complex number, `abs()` returns the magnitude of that number. 

**Example**:
# integer number
```
integer = -50  
print('Absolute value of -50 is:', abs(integer))  
```
**output:**
```
Absolute value of -50 is: 50
```
# floating number
```
floating = -63.29  
print('Absolute value of -63.29 is:', abs(floating))  
```
**output:**
```
Absolute value of -63.29 is: 63.29
```
# 4. bin()
The python `bin()` function is used to return the binary representation of a specified integer.

The result always starts with the prefix `0b`.

**Example:**
```
x =  75   
y =  bin(x) 
print (y)  
```
**output:**
```
0b1001011
```
# 5. bytes()
Python's `bytes()` function is used to return a bytes object.
It's a static version of the `bytearray()` function.

It is capable of producing an empty bytes object of the specified size. 

**Example**
```
string = "hello python world"  
array = bytes(string, 'utf-8')  
print(array)
```
**output:**
```  
b'hello python world'
```
# 6.sum():
`sum()` is used to add numbers in a list
**Example**
```
b= sum([5,9,3,6])
print(b)
```
**output:**
```
23
```
6.