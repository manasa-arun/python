---
title: "continue keyword in python"
description: "The`continue` keyword is one of the keyword out of thirty-five keywords in python"
date: "2022-09-09T8:30:05+09:00"
draft: false
link: "python continue keyword"
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

## `continue` keyword in python

1. The`continue` keyword is one of the keyword out of thirty-five keywords in python.

In a for loop (or a while loop), the continue keyword is used to end the current iteration and go on to the next one. 

The `continue` keyword can continue the iteration process it is completely opposite to break keyword in python.

## Syntax of `continue`  keyword

```python
while condition:
    statements  
     continue
    statements
```

### `continue()` keyword Examples:

let's go through some of examples to understand `continue()` keyword in python.

### Example 1:

```python
i = 0
while i < 5:
  i += 1
  if i == 2:
    continue
  print(i) 
```

output:
```python
1
3
4
5
```
In this example, we want to display numbers from 0 to 5, but since I is 2, we have to stop iterating at that point and move on to the next number. 

Try this example with another numbers and check.

### Example 2:

```python
c=0
while c<3:
        print("pythonshiksha")
        c=c+1
        continue
print("best python tutorial")
```
output:

```python
pythonshiksha
pythonshiksha
pythonshiksha
best python tutorial
```

## Summary
In this tutorial we learnt about Python `continue` keyword usage and examples to better understand
