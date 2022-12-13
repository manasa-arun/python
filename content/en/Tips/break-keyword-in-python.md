---
title: "break keyword in python"
description: "The 'break' keyword is one of the keyword out of thirty-five keywords in python."
date: "2022-09-09T8:30:05+09:00"
draft: false
link: "python break keyword"
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

## `break` keyword in python

1. The`break` keyword is one of the keyword out of thirty-five keywords in python.

The `break` keyword is used to stop the iteration process in python.

The iteration process can end when the keyword `break` appears automatically while iterating the list of items. 

## Syntax `break` keyword in python 
```python
Loop{
    Condition:
        break
    }
```
### `break()` keyword Examples:

let's go through some of examples to understand `break()` keyword in python.

### Example 1:

```python
students_list = ["aaaa", "bbbb", "cccc","dddd"]
for x in students_list:
    if x == "cccc":
        break
    print(x)
```
output:
```python
aaaa
bbbb
```
In this example student_list have four students but we got output only two members from list,how it is possible lets see

In this example, the `break` keyword is used to stop the iteration process. Here, the keyword is performed as the third student name is printed, stopping the process, and printing only the second item of the list, so only first two students name can be entered here.

### Example 2:

```python
for i in range(10):
    print(i)
    if i == 5:
        break
```

output:
```python
0
1
2
3
4
5
```
## Summary
In this tutorial we learnt about Python `break` keyword usage and examples to better understand