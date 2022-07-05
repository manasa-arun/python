---
title: "range function in python"
description: "range built in functions in python"
date: "2022-06-28T011:25:05+09:00"
draft: false
link: "range() built-in functions"
author: "harika"
---

## Range() in python:

The range() function returns a series of numbers that, by default, starts at 0 and increments by 1 before stopping before a given number. 
## syntax:

range(start, stop, step)

`start`- Optional.
a positive integer indicating the starting position.
default is zero. 

`stop`- Required.
a number in the integer range indicating where to stop (not included). 

`step`- Optional. 
An integer number specifying the incrementation. Default is 1


We can pass two parameters to this function.
1.lower limit
2.upper limit

**Example:**
```
for i in range( 5,10):
    print(i)
```
**output:**
```
5
6
7
8
9
```
Because 5 is the lower limit and 10 is the upper limit, the range function sequence begins with 5 and finishes with 10.

In this, 5 is automatically increased to 1; that is, 5 is added to 1 and the next number is 6, 

which is then added to 1 and the next number is 7, just as 1 is automatically added to the lower limit.

**Another example to range function**
```
for i in range(10):
    print(i)
```
**output:**
```
0
1
2
3
4
5
6
7
8
9
```
We are not provided two parameters in this case, but it successfully demonstrates how it works with only one parameter.


The solution is that `range(10)` in this range function can take `10 as the upper limit and 0 as the lower limit`, 

resulting in a series that starts at 0 and ends at 10. This range function can also work with just one parameter.

## One more example to range():
In this we can mention steps in it, while passing parameters to range()
```
for i in range( 5,10,2):
    print(i)
```
**output:**
```
5
7
9
```
In this program 5 is lower limit,10 is upper limit and 2 is step which means the lower limit can add with step and executes next number up to upper limit reached it will executes.

5 is added with 2, so the next number should be 7,
7 is added with 2,so the next number should be 9,
9 is added with 2 then 11 wants to execute but, 
11 is not executed why because, 
in this 10 is upper limit so the function can stop at 9 only.
