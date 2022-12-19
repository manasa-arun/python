---
title: "python 'continue' keyword usage,examples"
description: "The 'continue' keyword is one of the keyword out of thirty-five keywords in python"
date: "2022-09-09T8:30:05+09:00"
draft: false
link: "'continue' keyword"
author: "harika"
---

## python `continue` keyword 

1. The`continue` keyword is one of the keyword out of thirty-five keywords in python.

In a for loop (or a while loop), the continue keyword is used to end the current iteration and go on to the next one. 

The `continue` keyword can continue the iteration process it is completely opposite to break keyword in python.

## python `continue` keyword Uses

In programming, the `continue` keyword is used to skip the current iteration of a loop and move on to the next iteration.
It is often used within the body of a looping structure, such as a for loop or a while loop

## python `continue`  keyword syntax

```python
while condition:
    statements  
     continue
    statements
```

## python`continue` keyword Examples:

let's go through some of examples to understand `continue` keyword in python.

### Example 1:
To get serial numbers 

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
when we want to print something n times

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
In this tutorial we learnt about Python `continue` keyword usage with the help of simple examples.
