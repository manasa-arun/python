---
title: "Eliminating an element using it's index value"
description: "How to remove an element in a list using Index Value."
date: "2021-07-30T04:18:05+09:00"
draft: false
link: "Removing an Element using Index"
author: "acreddy"
---

## Introduction

The Python List datatype allows us to store items of various data types in a logical order.
The data is enclosed in square brackets ([]), with commas between the values (,).Many methods on the list data type in Python exist to assist you remove an element from a specified list. 
Remove(), pop(), and clear() are the three techniques. 
You can remove items from a list using the del keyword in addition to the list methods.
Let us take an example of a list and see how each of the above methods work.

``` 
My_list=[‘Arjun’,66,3.1415,’Reddy’, 99,[‘A’ ,’B’ , ‘C’] , 85]

```

The index of the list always starts with 0. In the ablove list we have a collection of datatypes. It also includes a nested list (a list within a list). 

## 1.	Remove() Method

The remove() method is an in-built method which can be used on lists. It aids in removing the first occurrence of the element to remove in the list.
The syntax is as follows –

``` 
List_name.remove(element)

```

This removes the first occurrence of the element is the specified list. The remove() method does not return any value.  It is beneficial to note that -
•	When there are duplicate elements in a list, the first element that matches the provided element is eliminated.
•	If the supplied element does not exist in the list, an error will be thrown stating that the element does not exist in the list.
•	There is no value returned by the remove () function.
•	The value is passed as an argument to remove () ,therefore it must be of the correct datatype.

**Example 1** 

``` 
my_list = [1,22,44,66,'Tim','Queens',100,'Queens','Cook',44,66,32]
my_list.remove(22) # it will remove the element 22 at the start.
print(my_list)

```

**Output**

```
[1, 44, 66, 'Tim', 'Queens', 100, 'Queens', 'Cook', 44, 66, 32]
[Finished in 146ms]

```
Even when we have multiple elements with the same name , the element with the smallest index will be removed first.

**Example 2**

```
my_list = [1,22,44,66,'Tim','Queens',100,'Cook',44,66,'Queens',32]
my_list.remove('Queens') # will remove the first Queen from the list
print(my_list)

``` 

Here the first occurrence of the element “Queens” is at index 5. This is the only occurrence that is removed from the list. The other occurrence of “Queens” at index 10 remains as it is. We can use other functions to remove all the occurrences of an element from the list, as shown further in the tutorial.

## 2.	Pop() Method

The pop() method removes an element from the list based on the parameter that is passed. The syntax for the pop() method is as follows –

```
Popped=my_list.pop(index)

```

The pop() method has an optional parameter, index. The pop() function returns a value. You must pass the element's index in order to remove it from the list. As the index begins at zero, passing index as 0 to removes the first element from the list. We can pass the index as -1 to eliminate the last entry. The index argument is optional. If no value is specified, the default value is -1, and the list's last element is returned. If the specified index is out of range/not present in the list, the pop() method produces an exception “IndexError:pop index “
Let us see an example for each of the above cases.

**Example 1 -By passing an index**

```

my_list = [1,22,44,66,'Tim','Queens',100,'Queens','Cook',44,66,32]
item_popped = my_list.pop(2)
print(item_popped)
print(my_list)

```

**Output**

```
44
[1, 22, 66, 'Tim', 'Queens', 100, 'Queens', 'Cook', 44, 66, 32]
[Finished in 158ms]

```

**Example 2 – By not passing an index**

```

my_list = [1,22,44,66,'Tim','Queens',100,'Queens','Cook',44,66,32]
item_popped = my_list.pop()
print(item_popped)
print(my_list)

```

**Output**

```
32
[1, 22, 44, 66, 'Tim', 'Queens', 100, 'Queens', 'Cook', 44, 66]
[Finished in 155ms]

```

**Example 3 -By passing an index out of range**

```

my_list = [1,22,44,66,'Tim','Queens',100,'Queens','Cook',44,66,32]
item_popped = my_list.pop(20)
print(item_popped)
print(my_list)

```

**Output**

```

Traceback (most recent call last):
  File "E:\OneDrive\Documents\GitHub\p1.py", line 2, in <module>
    item_popped = my_list.pop(20)
IndexError: pop index out of range
[Finished in 160ms]

```

## 3.	Clear() Method

The clear method will remove all the elements in the mentioned list. The syntax is as follows –

```

My_list.clear()

```

This method does not accept any parametes, nor does it return any value. It removes all the element in the list to make it a empty list. This can be used to remove any temporary/junk data that is to be stored in a list.

**Example**

```

my_list = [1,22,44,66,'Tim','Queens',100,'Queens','Cook',44,66,32]
item_popped = my_list.clear()
print(item_popped)
print(my_list)

```

**Output**

```
None
[]
[Finished in 156ms]

```

## 4.	Del function

To remove elements in a given range of indices, we can make use of the del function. The syntax is as follows –

```

Del my_list[start:stop]

```

The Del function can be used to slice a list. This does not return a value. The items in the list that are deleted cannot be stored inside a variable. The two parameters that the function takes i.e, start and stop are optional. They indicate where the removal of elements should start and where the removal should terminate. 

**Example**

```

my_list = [1,22,44,66,'Tim','Queens',100,'Queens','Cook',44,66,32]
del my_list[0:5]
print(my_list)

```

**Output**

```
['Queens', 100, 'Queens', 'Cook', 44, 66, 32]
[Finished in 153ms]

```

If ending is not mentioned , then the removal of elements start from starting index until the end of the list. 

**Example**

```

my_list = [1,22,44,66,'Tim','Queens',100,'Queens','Cook',44,66,32]
del my_list[7:]
print(my_list)

```

**Output**

```
[1, 22, 44, 66, 'Tim', 'Queens', 100]

```

If the starting is not mentioned, then the removal starts at index 0 until the ending index mentioned in the parameters.

**Example**

```

my_list = [1,22,44,66,'Tim','Queens',100,'Queens','Cook',44,66,32]
del my_list[:7]
print(my_list)

```

**Output**

```
['Queens', 'Cook', 44, 66, 32]

```
We can also use the del function to remove an individual element , by specifying index as the parameter without the semicolon.

**Example**

```
my_list = [1,22,44,66,'Tim','Queens',11,222]
del my_list[5]
print(my_list)

```

**Output**

```
[1, 22, 44, 66, 'Tim', 11, 222]

```


This can be used to remove the first element of the listby mentioning the index as 0, and the last element by mentioning the parameter as -1. 

**Example**

```

my_list = [1,22,44,66,'Tim','Queens',11,222]
del my_list[0]
print(my_list)

my_list = [1,22,44,66,'Tim','Queens',11,222]
del my_list[-1]
print(my_list)

```


**Output**

```
[22, 44, 66, 'Tim', 'Queens', 11, 222]
[1, 22, 44, 66, 'Tim', 'Queens', 11]

```


## 5.	The Long Method

Pop and del, as previously discussed, are efficient techniques to delete an item from a specified index. When working with Python lists, this will be the slowest approach, but it may be handy when working with user-defined objects that don't have pop and del functions. However, for the sake of exploring possibilities (since the same thing can be done via many ways in Python) . This can be demonstrated with the following example.

**Example**

```

a=[1,2,3,4,5]
index =2

newlist=a[:index] +a[index +2 :]
print(newlist)

```

**Output**

```

[1, 2, 5]

```

Here we create a new list, which concatenates different parts of the original list. As mentioned earlier, this may not be the most suitable way to perform a removal operation, but we discuss it here to explore additional methods by which a goal can be obtained.

## Conclusion 
Many methods on the list data type are available in Python to let us remove an element from a specified list. 

