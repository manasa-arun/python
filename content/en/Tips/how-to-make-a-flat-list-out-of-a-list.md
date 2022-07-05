---
title: "How to make a flat list out of a lists"
description: "Python has a number of techniques to make a flat list out of a lists"
date: "2022-04-16T02:26:05+09:00"
draft: false
link: "making flat list out of a lists"
author: "harika"
---

## introduction:
python supports creation one dimensional,two dimensional lists and so on..
A list is a more flexible data structure in python.

now we can make a flat list out of a lists, using simple and easy methods 

## using nested loop

This is a brute-force method of creating a flat list by selecting every element from the list of lists and placing it in a 1D list.

```
list2d= [[1,2,],[3],[4,5,6]]

list1d =[]
for each_list in list2d:
    for item in each_list:
        list1d.append(item)
print(list1d)
```
output:

```
[1, 2, 3, 4, 5, 6]
```

## using list comprehension:

It is a most pythonic method,it is a quick method accessing  and putting any item in to any type data structure

```
list2d= [[1,2,],[3],[4,5,6]]

arr = [item for item_list in list2d for item in item_list]

print(arr)

```
output:

```
[1, 2, 3, 4, 5, 6]
```
## using lambda function:

The keyword `lambda` is used to define an anonymous function.

The function will accept a list as an argument, and the lambda function will transform it from 2D to 1D or from the original list to the flattened list.

Example:
```
lists = [[1, 2, 3], [4], [5,6], ['a', 'b', 'c']]
newlist = lambda lists:[element for item in lists for element in newlist(item)] if type(lists) is list else [lists]

print(newlist(lists))
```
output:
```
[1, 2, 3, 4, 5, 6, 'a', 'b', 'c']
```
## using iter tools and chain():

This method is perfect for converting a 2-D list into a single flat list.

since it interprets consecutive sequences as a single sequence by iterating sequentially through the iterable supplied as the argument.

 **Example:

```
list2d= [[1,2,],[3],[4,5,6]]
import itertools

merge =list(itertools.chain(*list2d))

print(merge)
```
output:
```
[1, 2, 3, 4, 5, 6]
```

## using built in functions:[sum()]

The `sum() `function adds list components within lists and returns a single list. To convert lists of lists into a single list, we shall add the nested list to an empty list.

```
regular_list = [[1, 2, 3, 4], [5, 6, 7], [8, 9]]

flat_list = sum(regular_list, [])

print('Original list', regular_list)
print('Transformed list', flat_list)
```
output:
```
Original list [[1, 2, 3, 4], [5, 6, 7], [8, 9]]
Transformed list [1, 2, 3, 4, 5, 6, 7, 8, 9]
```
## Using reduce operation:

It adds elements from the original list here by reducing the action of the functools module to a flat list.

```
import operator
from functools import reduce

if __name__ == '__main__':
    list = [[1, 2, 3], [4], [5,6], ['a', 'b', 'c']]
    joinedlist = reduce(operator.add, list)
    print(joinedlist)
 ```
 output:
 ```
 [1, 2, 3, 4, 5, 6, 'a', 'b', 'c']
 ```
 ## using Concatenation [Numpy]:

 Concatenation is one of the many operations available in the Numpy library. Lists can be flattened using this operation.

```
import numpy
lists = [[1, 2, 3],[4], [5,6], ['a', 'b', 'c']]
newlist = list(numpy.concatenate(lists).flat)    
print(newlist)
```
output:
```
[1, 2, 3, 4, 5, 6, 'a', 'b', 'c']
```
## conclusion:

In conclusion we discussed here how to flatten list out of a lists with simple concepts with python programs code to understand everyone easily.

 


