---
title: "How to remove elements from list while iteration"
description: "Three important methods for removing elements in list while iteration in python"
date: "2022-03-14T12:15:05+09:00"
draft: false
link: "remove elements while iteration"
---

## Remove elements from list while iteration
**What is ITERATION**
**Iteration** is a process of taking elements from list one after another in specified manner.

**Example**:
```
for i in range(10)
print(i)
```
**output**:
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
so our list is generated from 0 to 9 only because  range should be 10.

if we want 1 to 10 numbers in list the code must have index value

**Example**:
```
for i in range(1,11):
print(i)
```
**output**:
```
1
2
3
4
5
6
7
8
9
10
```
now successfully got our list from 1 to 10.

## how to remove elements from list while iteration?
We have three major concepts to remove elements from list
1.using for loop
2.list comprehension method
3.using filter()

Now we can discuss remove elements from list using **for loop***

first we can create a student marks list like
`marks_list is 20,60,30,70,99,64,12` in this list 'four' subjects marks are above '50',

who got above `50` marks those are passed, so `four` subjects passed.

remaining `two` subjects failed,our job is to remove that 2 failed subjects from list what we have to do is..

**example**
```
marks_list =[20,60,30,70,99,64,12]:
   def check(mark):
   if mark > 50:
   return True
 else:
    return False

for item in marks:
   if check(item) is True:
   PASS
   marks.remove(item)
print(marks)
```
**output**:
```
[60,70,99,64]
```
list is clear now only four subjects passed,remaining two subjects failed.

## 2.list comprehension method to remove elements from list:

by using `comprehension` method very easy to  remove failed subjects from student list to do this.

**Example**:
```
marks_list =[20,60,30,70,99,64,12]
updated_marks  (x for x in marks if check(x) is True):
print(updated_marks)
```

**output**:
```
[60,70,99,64]
```
After removing two subjects, we have a student list with passed subjects only.


## 3.Remove elements from list with Filter()
Even a tough task also easy by using Lambda function to remove elements from list in just 1 liner of code,

`lambda` actually construct a new list and Filters out all of the  required elements.

It remove all the occurrences of element.

Here is the `marks list 20,60,30,70,99,64,12` in this we can `remove` failed subjects marks to do this 

**Example**:
```
marks_list = [20,60,70,99,64,12]
marks_list = list(filter(lambda marks: marks>=50, marks_list))
print("list is: " +str(marks_list))
```
**output**:
```
[60,70,99,64]
```
here successfully `removed` failed subjects from list which is less than `50` marks, and got a out put list with `passed subjects` list.


 











