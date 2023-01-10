---
title: "check if something is not in a list in Python"
description: "Three  methods of check if something is not in a list in Python"
date: "2022-05-16T04:40:05+09:00"
draft: false
link: "something is not in a list"
author: "harika"
---

In this article, we will briefly discuss about the **different Python methods that we can use to check if something is not in a list in Python** along with some shortcuts that can make our coding efficient.

## introduction to list:
Python provides a very wide range of compound and simple Data structures and List is one the most flexible and popular Data structures in Python.

List contains a group of elements of a different data type *separated* by **commas**, and *enclosed* inside square brackets **[ ]**. 

**Example of a list:**
```
sample_list = [ '21','orange','3.5','-2']
```

## check if something is not in a list in Python:
## using "not in" operator:

If an element is not found in a list, it is returned.
If the element does not appear in the list, True; otherwise, False.

**Example:**
```
my_list = ["29", "31", "11","4","6"]

not_in_list = "31" not in my_list

print(not_in_list)
```
output:
```
False
```
here 31 number in my list so output is `false`, that means which number we are checking the number is in my list.

change the searching number and try once a gain like this

```
my_list = ["29", "31", "11","4","6"]

not_in_list = "22" not in my_list

print(not_in_list)
```
output:
```
True
```
here 22 is serching in my list, 22is not there in my list so the putput is `True`

The 'not in' operator can be used to quickly determine whether a searched element is in a list or not in Python.

## using len():

We use len() to check if a list is empty in this solution; this function returns the length of the argument supplied.
Because the length of an empty list is zero, it can be used to determine whether a list is empty in Python.

**example:**
```
list1 = ["22", "Python", "best language", "1%", "java"]

list2 = []

if len(list1):
    print("list is not empty")
else:
    print("list is empty")
```
output:
```
list is not empty
```
if we use `list2 instead of list1` the output will come `list is empty`

so we can easily find out the element is not in a list in Python.


## using len()== 0:
len()==0 function can also used like this to check something in list or not like this 

**example:**

```
list1 = ["22", "Python", "best language", "1%", "java"]

list2 = []

if len(list1) == 0:
    print("list is empty")
else:
    print("list is not empty")

```
output:
```
list is not empty
```
here, `len(list1)==0` means length of list1 is 0 then it returns  `list is not empty` so list1 have something in it.

if `len(list2)==0` means length of list2 is 0 then it returns  `list is empty` so list2 don't have any data in it.

## using len() and not in operator:

combine this two techniques like this to check something in list or not.
```
list1 = ["22", "Python", "best language", "1%", "java"]

list2 = []

if len(list1):
    print("list is not empty")
else:
    print("list is empty")

not_in_list = "22" not in list1
print(not_in_list)  
```
output:
```
list is not empty
False
```
Here is what we can understand: first, check if the `list1` is empty or not; if the list1 is not empty, it returns; 

secondly, check if `22` is in the list or not; if `22` is in the list, it will display `False`, indicating that 22 is in list1. 

## conclusion:
here we discussed about `checking if something is not in a list or not in Python` with simple programing  codes to everyone can understand easily, prepare your own list and try this methods