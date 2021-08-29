---
title: "Concatenating two lists"
description: "How to concatenate two lists."
date: "2021-08-06T04:15:05+09:00"
draft: false
link: "Concatenating two lists"
author: "acreddy"
---

## Introduction

Python Lists are used to store homogeneous elements and perform transformations on them. Concatenation, in general, is the process of linking the elements of a data structure from beginning to conclusion. 
Let's look at how to concatenate two lists in Python using different approaches.
When we have many lists of elements that need to be processed in the same way, this procedure comes in handy. Here we will be looking at the following operations –
1.	Naïve Method
2.	Extend Method
3.	Using  *  operator 
4.	List Comprehension 
5.	Concatenation Operator (+)

## Method - 1 – The  Naïve Method

A for loop is used to traverse the second list in the Naive method. After that, the second list's elements are appended to the first list. The first list is the result of concatenating the first and second lists. 

**Example**

```

list1 = [1, 2, 3, 4, 5] 
list2 = [10, 20, 30, 40] 
 
print("List before Concatenation: " + str(list1))
for x in list2 : 
    list1.append(x) 
 
print ("The Concatenated list: " + str(list1))

```

**Output**

```
List before Concatenation: [1, 2, 3, 4, 5]
The Concatenated list: [1, 2, 3, 4, 5, 10, 20, 30, 40]

```

## Method 2 – Using the extend() method

The extend() method appends to the end of a list all the elements of an iterable (list, tuple, string, etc.).  The syntax is as follows –

``` 
List1.extend(iterable)

```

The extend() method accepts one parameter, an iterable such as a list, tuple string etc.
The extend() method does not return any values. It modifies the original list to include the second list.

**Example**

```
Test1=[1,2,3,4,5]
Test2=[10,20,30,40,50]
Test1.extend(Test2)

print("Concatenated list is : {Test1}" + str(Test1))

```

**Output**


```
Concatenated list is : {Test1}[1, 2, 3, 4, 5, 10, 20, 30, 40, 50]

```

## Method 3 – Using the * Operator

The '*' operator in Python can be used to easily concatenate two lists. In Python, the ‘*' operator unpacks the collection of items at the index arguments. 

Consider the following list: 

```
my list = [1, 2, 3, 4].

```

The statement *my list replaces the list at the index positions with its elements.
As a result, the items in the lists are unpacked.

**Example**

```
list1=[1,2,3,4,5]
list2=[100,200,300,400,500]
 
result = [*list1, *list2] 
   
print ("Concatenated list:  " + str(result))

```

The expression res = [*list1, *list2] in the above snippet of code replaces the items in the specified order, i.e., elements of list1 after elements of list2. This performs concatenation and produces the output seen below.

**Output**

```
Concatenated list: [1, 2, 3, 4, 5, 100, 200, 300, 400, 500]

```

## Method 4 – List Comprehension 

Essentially, Python List Comprehension is a concept that is not often used in other programming languages. It's primarily used to build a list of components with a particular characteristic. Furthermore, Python List Comprehension reduces code size while increasing efficiency.

Python List Comprehension is a different way of joining two lists in Python.
The technique of creating/generating a list of elements from an existing list is known as list comprehension.
It processes the list using the for loop and traverses it element by element.
The inline for loop below is the same as a nested for loop.

**Example**

```

list1=[1,2,3,4,5]
list2=[12,23,34,45,56]
 
result = [j for i in [list1, list2] for j in i] 
 
print ("Concatenated list: "+ str(result))

```

**Output**

```
Concatenated list: [1, 2, 3, 4, 5, 12, 23, 34, 45, 56]

```

## Method 5- Using the Concatenation operator (+)

The '+' operator can be used to join two lists together. It appends one list to the end of the other, producing a new output list. Using the "+" operator, we can quickly add the entirety of one list behind the other and thus achieve concatenation. 

**Example**

```

list1=['A','B','C','D']
list2=['W','X','Y','Z']

result=list1 + list2 

print ("Concatenated list: "+ str(result))

```

**Output**

```

Concatenated list: ['A', 'B', 'C', 'D', 'W', 'X', 'Y', 'Z']

```

## Conclusion

Thus , we have explored and implemented different ways of Concatenating lists in python.
