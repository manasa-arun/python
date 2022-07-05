---

title: " python typeerror int object is not iterable "
description: " range function can solve python typeerror int object is not iterable "
date: "2022-05-09 T019:05:05+09:00"
draft: false
link: "typeerror int obj is njot iterable"
author: "harika"
---
## introduction:

This type of error occurs when the code is trying to iterate over a list of integer elements.

We can say that the error occurs most frequently while performing code, rather than when following right guidelines.

One of the restrictions is that the int object must be iterated throughout the programme.

If we do so, the error "int object is not iterable" will appear. 

'iterable' means to go through each string or word till the end by iterating over it one by one.


`Typeerror` is a error When a function is applied to an object with the improper data type, a TypeError is thrown.

A TypeError is raised, for example, if you try to apply a mathematical function to a text or call a value that is not a function. 

`int object is not iterable` means The int object cannot be iterated.
when we  attempted to iterate over an object that is not iterable, according to the python message.

Iterable objects are those whose values may be accessed by a "for loop." 

**Error scenario Example:**
```
fruits=['apple','banana','papaya']
vegetables=['tomato','potato','carrot']
print("fruits   vegetables")
for i in (len(fruits)):
    print(fruits[i],"   ",vegetables[i])
```
output:
```
    for i in (len(fruits)):
TypeError: 'int' object is not iterable
```
Because there is no range method in it, we get the error int object is not iterable.

The `range` function in Python examines the variable supplied to it and produces a sequence of numbers beginning at 0 and ending just before the desired number or string.

The error is on line 4, which can be changed as follows: 

***solved scenario Example:**
```
fruits=['apple','banana','papaya']
vegetables=['tomato','potato','carrot']
print("fruits   vegetables")
for i in range(len(fruits)):
    print(fruits[i],"   ",vegetables[i])
```
output:
```
fruits   vegetables
apple     tomato
banana     potato
papaya     carrot
```
so with out range function the program can not be iterate properly, so we got a error `int object is not iterable`

## conclusion:

`Typeerror` is one of the most common errors in Python programs,
If you are encountering the “‘int’ object is not iterable” error message, this probably means that there is something wrong with your `for loop`, and you have forgotten to put the `range() method`. So do it, and it will be fixed.


