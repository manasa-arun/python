---
title: "len() function in Python"
description: "In this tutorial we learn how to use len() function in Python"
date: "2022-06-26T07:30:00+00:00"
draft: true
link: "len()"
author: "harika"
---

## Python len() Function:

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