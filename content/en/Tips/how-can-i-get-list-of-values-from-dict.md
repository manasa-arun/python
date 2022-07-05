---

title: "How can i get list of values from dict"
description: "  Three techniques for getting list of values from dict"
date: "2022-04-22 T010:32:05+09:00"
draft: false
link: "getting values from dictionary"
author: "harika"
---

## introduction:
A dictionary is an object that stores a collection of data.

Each element of dictionary has two parts: a` key`and a `value`.We use a key to locate a specific value.

the values in dictionary of any type,but keys must be immutable objects.

Emp_id={'ravi':'1234','kiran'='1235','arun'='1236'}

here `employee name` is `key`
`employee id` is `value`

like this we can create a dictionary with employee name and with their employee id's respectively.

## how can i get list of values from dict:
## using *operator:

We can use [] along with * to get all list of dictionary values.
Example:
```
students_roll= {1: "saanvi", 2: "rahul", 3:"kathya"}
[*students_roll.values()]
```
output:
```
['saanvi','rahul','kathya']
```
In this `1,2,3` are `keys` and `saanvi,rahul,kathya` are the `values` of dictionary so we got a output with this values as shown in above example.


## using list()

we can use dictionary.values() along ith list() to get the list.

`values()` is access the values from `key:value` pairs and e are then converting the values to list by using list()

syntax:

list(dictionary.values())

Example:
```
students_roll= {1: "saanvi", 2: "rahul", 3:"kathya"}
print(list(students_roll.values()))
```
output:
```
['saanvi','rahul','kathya']

```
In this `1,2,3` are `keys` and `saanvi,rahul,kathya` are the `values` of dictionary so we got a output with this values as shown in above example.

## using list comprehension():
In this method we are using list comprehension to iterate in a dictionary by using iterator.

iterator will return each value from the `key:value` pair.

To iterate values from list or dict we can use for to iterate the values.

Example:
```
students_roll= {1: "saanvi", 2: "rahul", 3:"kathya"}
print([students_roll[i] for i in students_roll])
```
output:
```
['saanvi', 'rahul', 'kathya']
```
In this `1,2,3` are `keys` and `saanvi,rahul,kathya` are the `values` of dictionary so We got a output With this values as shown in above example.

## Conclusion:

getting list of values from dictionary is a easy method in python,

In this article detailed information available with one simple example to understand everyone easily lets check and try to change your own dictionary data and try this methods in python programing code.

