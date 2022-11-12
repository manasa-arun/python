---
title: "for keyword in python"
description: "Keywords are python reserved words"
date: "2022-09-09T8:30:05+09:00"
draft: false
link: "python for keyword"
author: "harika"
---

## introduction to keywords:

Keywords are python reserved words.
We cannot use them as constants or variables or any other identifier names.
we have Thirty-five keywords in python.

## list of the Python keywords:

False               class               from                or
None                continue            global              pass
True                def                 if                  raise
and                 del                 import              return
as                  elif                in                  try
assert              else                is                  while
async               except              lambda              with
await               finally             nonlocal            yield
break               for                 not  

## `for` keyword in python

1. The`for` keyword is one of the keyword out of thirty-five keywords in python.

2. The `for` keyword is iteration type of keyword in python.

3. The `for` keyword is used to create for loop in python like in other programing languages also.

4. The `for` keyword we can display more number of list,tuple or set items in one attempt by iteration process.

5. The `for` keyword mainly used for iteration process only.

## Syntax of `for` keyword in python

```python
for variable in sequence:
        statements
```
### `for()` keyword Examples:

let's go through some of examples to understand `for()` keyword in python

### Example 1:

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

```python
for i in[10,20,30]:
        print("value =", i)
else:
        print("For completed values")
```
output:

```python
value = 10
value = 20
value = 30
For completed values
```
## Summary
In this tutorial we learnt about Python `for` keyword usage and examples to better understand.
