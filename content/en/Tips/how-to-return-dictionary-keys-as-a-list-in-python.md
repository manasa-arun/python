---

title: "How to return dictionary keys as a list in Python"
description: " Three techniques for return dictionary keys as a list in Python"
date: "2022-05-04T10:32:05+09:00"
draft: false
link: "return dictionary keys as a list"
author: "harika"
---

## introduction:

Dictionary is an object that stores collection of data in Python,which consists of `key-value` pairs which can be used to store data. 

Like other data structures in Python, Dictionaries/Map also contains indexes called **Keys**. 

Keys can be both numeric as well as string but it can’t be of the form of a **mutable sequence** or object. 

In this article we will briefly discuss the various methods to **How to return dictionary keys as a list in Python** and which method is more reliable.

For that, we will use a reference dictionary i.e.:

emp_id = {'harika':'1234','saanvi':'1235','santhosh':'1236'}

## using dict.keys():

This was simple in Python 2.x because the function dict.keys() gave a list of the dictionary's keys by default, but this is not the case in Python 3.x. 

**Example:**

```
emp_id = {'harika':'1234','saanvi':'1235','santhosh':'1236'}
print(emp_id.keys())
```
output:
```
dict_keys(['harika', 'saanvi', 'santhosh'])
```
in this Python code created a dictionary with `emp_id` in that keys are employee names and values are employee id's.

`emp_id.keys` is used to display keys in dictionary,we have keys here employee names 
harika,saanvi,santhosh

like this you can try with your own dictionary.

## using dict.values():

if we want to values from dictionary use this `dict.values` check this example

**Example**
```
emp_id = {'harika':'1234','saanvi':'1235','santhosh':'1236'}
print(emp_id.values())
```
output:
```
dict_values(['1234', '1235', '1236'])
```
now we got a output dictionary values, i.e employee id's,check this code and try with your on dictionary.

## using *operator:

This function works with any iterable object, and because dictionaries yield their keys when iterated through, we can generate a list of keys with it. 

**Example**:
```
def list_of_keys(emp_id):
    return [*emp_id]
emp_id = {'harika':'1234','saanvi':'1235','santhosh':'1236'}

print("The list of keys are: "+ str(list_of_keys(emp_id)))
```
output:
```
The list of keys are: ['harika', 'saanvi', 'santhosh']
```
so we got a list of keys in dictionary, try this code with your own dictionary.

## using list():
list() is also used to get keys from dictionary.

**Example:**
```
emp_list= {'harika':'1234','saanvi':'1235','santhosh':'1236'}
keys_list = list(emp_list)
print (keys_list)
```
output:
```
['harika', 'saanvi', 'santhosh']
```
## list comprehension:
while iteration of keys in dictionary we can use this list comprehension method, in this `dict.keys` is usd to get keys in dictionary.


**Example:**
```
emp_list= {'harika':'1234','saanvi':'1235','santhosh':'1236'}
keys = emp_list.keys()
print([k for k in keys])
```
output:
```
['harika', 'saanvi', 'santhosh']
```
## conclusion:

we have more concepts to get keys from dictionary but `dict.keys`  and `list()` are the simple and best method to get keys from any type of dictionary.

check this article and try with your own dictionary and learn more concepts in Python in this simple way.
