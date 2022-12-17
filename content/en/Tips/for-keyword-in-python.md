---
title: "Python 'for' keyword usage, examples" 
description: "The 'for' keyword is one of the keyword out of thirty-five keywords in python"
date: "2022-09-09T8:30:05+09:00"
draft: false
link: "'for' keyword"
author: "harika"
---


## python `for` keyword 

1. The`for` keyword is one of the keyword out of thirty-five keywords in python.

2. The `for` keyword is iteration type of keyword in python.

3. The `for` keyword is used to create for loop in python like in other programing languages also.

4. The `for` keyword we can display more number of list,tuple or set items in one attempt by iteration process.

5. The `for` keyword mainly used for iteration process only.

## python `for` keyword Uses

1. In Python, the `for` keyword is used to create a loop that iterates over a sequence of elements. 
2. The `for` loop is used to repeat a block of code for each element in the sequence.

## python`for` keyword Syntax 

```python
for variable in sequence:
        statements
```
## python `for` keyword Examples:

let's go through some of examples to understand `for` keyword in python

### Example 1:
To print students list using `for`

```python
students_list = ["aaaa", "bbbb", "ccccc"]
for x in students_list:
  print(x) 
```
output:

```python
aaaa
bbbb
cccc
```
If we don't want to use a "for" loop to get this output, we must print the list's contents "x" times. 

By using a for loop and an iteration process, we can obtain this output with only one easy line of code. 

### Example 2:
using `for` keyword to find sum and average of numbers.

```python
numbers =[22,33,26,87,100]
sum =0
for n in numbers:
        sum= sum+n
print('sum =', sum)
print('average =', sum/len(numbers))
```
output:

```python
sum = 268
average = 53.6
```

### Example 3:
using `for` keyword to print values

```python
for i in[10,20,30]:
        print("value =", i)
else:
        print("values completed ")
```
output:

```python
value = 10
value = 20
value = 30
values completed
```
## Summary
In this tutorial we learnt about Python `for` keyword usage with the help of simple examples.

