---
title: "Getting a index of an item from in a list"
description: "How to obtain the value of the index of an item in a list."
date: "2021-07-19T04:15:05+09:00"
draft: false
link: "Finding the Index"
author: "acreddy"
---

## Introduction

You can use the ** index() ** function of the List class with the element passed as an argument to get the index of the first occurrence of an element in a specified Python List.
` ` `
Index=test_list.index(element)
` ` `
In the above code, the test_list is the list in which we are to find the first occurrence of the element. The** index() ** method returns the value of the index which corresponds to the first occurrence of the element in the list.
The  ** index() **  method also accepts additional parameters, such as, the start index and end index. The start and end indices are to indicate if one requires to find an element in a portion of a long list. The syntax is as follows – 
` ` `
Index =mylist.index(element,start_index,end_index)
` ` `
The start and the end indices are optional. 
Next , we can look at a few examples on the use of the ** index() ** function.
**Example 1**
` ` `
list1 = [1, 2, 33, 4, 1, 19, 1, 4, 25]
 
print(list1.index(4))
` ` `
**Output**
` ` `
3
` ` `
**Example 2**
` ` `
list2 = ['cat', 'bat', 'mat', 'cat',’pat’, 'cat', 'sat', ‘tat’]
 
# Will print index of 'cat' in sub list having index from 2 to 6
print(list2.index('cat', 4, 8 ))
` ` `
**Output**
` ` `
5
[Finished in 152ms]
` ` `

Now, what if we pass a value that does not exist in the list? Well, here is an example of this case.
**Example 3**
` ` ` 
list1 = [1, 4,3, 4, 1, 1, 1, 4, 5]
 
print(list1.index(10))

` ` `
**Output **
` ` `
Traceback (most recent call last):
  File "E:\OneDrive\Documents\GitHub\p1.py", line 3, in <module>
    print(list1.index(10))
ValueError: 10 is not in list
[Finished in 156ms]
` ` `
Since we already know that the element is not present in the list, we know there will be an error. 
## Conclusion
We have seen the different ways in which we can use the * index() * function to find the index value of an element in a list.


