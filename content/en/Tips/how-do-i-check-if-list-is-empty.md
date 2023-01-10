---
title: "How do I check if a list is empty"
description: "Python has a number of techniques for determining whether a list is empty"
date: "2022-03-19T02:26:05+09:00"
draft: false
link: "checking list is empty"
author: "harika"
---

## How do I check if a list is empty:

Learn how to check if a list is empty in Python in this brief tutorial. We also look at why you need to do this so that you have a better understanding of the purpose.
 
## What is a List ?

Python provides a very wide range of compound and simple Data structures and List is one the most flexible and popular Data structures in Python.

List contains a group of elements of a different data type *separated* by **commas**, and *enclosed* inside square brackets **[ ]**. 

Example of a list:

```
sample_list = [ '21','orange','3.5','-2']
```

## Why we need to check empty list or not:

If the list have elements, it is possible to iterability and all types of concepts.

So, before we do anything to alter, we can check to see if the list is empty or not, and then we can proceed with the modification or anything.

so it is a good practice to check if a list is empty before proceeding.

## 1.using len() function:

Python has an inbuilt `len()` function for calculating the number of elements inside a list.

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

## 2.using bool 

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
like this bool() returns to`false or true` 

## Example:
```
a=[]
if not a:
    print("list is empty")
```
 **output**
 ```
 list is empty
 ```
one more example
```
a=[20,30]
if not a:
    print("list is empty")
```
**Output**
```
nothing will display here why because list has values 
```

## 3.using equal to operator or compare method:

we can also check the list with this `equal to`operator.
the `equal to` operator is denoted by to equal signs i,e."=="

**example**

```
nums_list=[]
if nums_list == []:
    print("list is empty")
```
**output**

```
list is empty
```
**conclusion**
   
   Python list is most used data stuctures in any development so in this process `checking the list is empty or not` is the best and time saving technique to do any development in Python.
















