---

title: "How do I get last element of a list"
description: " six techniques for getting last element of a list"
date: "2022-04-05 T010:32:05+09:00"
draft: false
link: "getting last element of a list"
author: "harika"
---

## introduction:

In this article, we'll take a look at some of the most common ways to get the last element in a list in Python.

First, we will cover the simplest methods with simple examples in a pythonic way.

## What is a List ?

Python provides a very wide range of compound and simple Data structures and List is one the most flexible and popular Data structures in Python.

List contains a group of elements of a different data type *separated* by **commas**, and *enclosed* inside square brackets **[ ]**. 

Example of a list:

```
sample_list = ['apple','orange','papaya','guava']

```
## get last element using negative index values:

To access the individual elements in a list is we can use `index`

each element in a list has an index tht specifies its position in the list.

Indexing starts from`0` so the index of first element is `0`

we can also use negative indexes to access elements from the `end to begin `. The index of the last element in the list starts from `-1`
i.e.
 
example:

```
sample_list = ['apple','orange','papaya','guava']
```
`-1` identifies the last element in the list `guava`
`-2` identifies the next to last element in the list `papaya`
`-3` identifies the next to last element in the list `orange`
`-4` identifies the next to last element in the list  `apple`

```
sample_list = ['apple','orange','papaya','guava']
last_elem = sample_list[-1]
print('last element', last_elem)
```
output:
```
last element guava

```
In this code We can give index value as `-1` so we got a out put `guava`

like this negative index is useful to get last element of a list.

it is a very efficient solution even if you list is of very large size. Also, this is the most simplest and most used solution to get the last element of list. Let’s discuss some other ways,

## get last element using slicing:

A `slice` is a span of items that are taken from a list.

to get a slice of a list the general format is:
```
list_name[start:end]
```


```
sample_list = ['apple','orange','papaya','guava']
last_elem = sample_list[2:4]
print('last element', last_elem)

```
output:
```
last element ['papaya', 'guava']
```

after this statement executes the last_elem variable references the following list:
['papaya','guava']

** one more example:

```
sample_list = ['apple','orange','papaya','guava']
last_elem = sample_list[3:]
print('last element', last_elem)
```
output:
```
last element ['guava']
```
like this we can easily get a last element of a list with `slicing`

`last_elem = sample_list[3:]` in this [3:] starts from 3 and end is nothing so we can get only last element from list.

## get last element using pop():

In Python, the pop() method is used to remove the last element of the given list and return the removed item.

example:
```
sample_list = ['apple','orange','papaya','guava']
last_elem = sample_list.pop()
print('last element', last_elem)
```
output
```
last element guava
```
Note:
if you need to remove the last element, as well as access it, then you should probably go with the pop() method, which is the built-in method for performing exactly this behavior.

## get last element Using itemgetter():

The itemgetter() method is one of the many methods in the operator module. 

It accepts one or more integers as the argument and returns a callable object which can be seen as a type of special function.

The itemgetter() operator supports negative indexing so retrieving the last element boils down to

In this method negative indexing is placed major role to get last element in it.

operator.itemgetter(-1) `-1` indicates negative index and it gives directly last number of list.

example:
```
import operator

exampleList = ['apple','orange','papaya','guava']
getLastElement = operator.itemgetter(-1)
lastElement = getLastElement(exampleList)
print("Last element: ", lastElement)

print("exampleList: ", exampleList)

```
output:

```
Last element:  guava
exampleList:  ['apple', 'orange', 'papaya', 'guava']
```
## using built in functions:

We'll utilise two built-in Python methods in this method: `reversed()` and `next ()`.

`reversed()` takes a list as an argument and returns the list's reversed iterator, which means that the iteration is done backwards, from the final element to the first. 

`next()` takes an iterator and returns the iterator's next element.

```
exampleList =['apple','orange', 'papaya', 'guava']
reversedIterator = reversed(exampleList)

lastElement = next(reversedIterator)
print("Last element: ", lastElement)

```
output:
```
last element: guava

```

## using list length:

To get the last element of a list, we can first find the length of the list using the len() function.

Then we can access the last element of the list at the index `listLen-1` as follows.

```
exampleList = ['apple','orange', 'papaya', 'guava']
print("Given List is:", exampleList)
listLen = len(exampleList)
lastElement = exampleList[listLen - 1]
print("Last element of the list is:", lastElement)
```
output:
```
Given List is: ['apple', 'orange', 'papaya', 'guava']
Last element of the list is: guava
```

## conclusion:

These are the methods to get the last element of a list in python.
in these `indexing`  and `slicing` methods are very simple to get element and `pop()` method is also simple but Remember that the `pop()` method also deletes the element which is accessed. So, Use this method only when you also want to delete the last element of the list. 















