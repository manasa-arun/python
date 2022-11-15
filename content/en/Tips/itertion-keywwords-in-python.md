---
title: "iteration keywords in python"
description: "for, while, break, continue, else keywords in detail"
date: "2022-09-09T8:30:05+09:00"
draft: false
link: "python iteration keywords"
author: "harika"
---

## introduction to keywords:

Keywords are python reserved words.
We cannot use them as constants or variables or any other identifier names.

## list of Thirty-five keywords in python:
we can list out keywords with `help()` 

```python
>>> help ("keywords")

Here is a list of the Python keywords.  Enter any keyword to get more help.

False               class               from                or
None                continue            global              pass
True                def                 if                  raise
and                 del                 import              return
as                  elif                in                  try
assert              else                is                  while
async               except              lambda              with
await               finally             nonlocal            yield
break               for                 not                 
```

you can use help() again by passing in the specific keyword that you need more information about. 

## iteration keywords in python:

iteration keywords include five of the Thirty-five  total keywords.
for, while, break, continue, else keywords are iteration keywords.

## `for` keyword in python:
The `for` keyword is used to create for loop in python like in other programing languages also.

with this keyword we can display more number of list,tuple or set items in one attempt by iteration process.

The `for` keyword mainly used for iteration process only.

### Example:
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

## `while` keyword in python:

`While` a condition is true, a series of statements can be run in a while loop. 
The loop iterates while the condition is true.
When the condition becomes false, program control passes to the line immediately following the loop.

In Python, a block of code consists of all the statements that follow a programming construct and are indented by the same number of character spaces. 

### Example:

```python
i = 0
while i < 4:
  print(i)
  i += 1
```
output:
```python
1
2
3
```
In this example i is 0 and less than four so after iteration with while loop only three numbers can get like this.

## `break` keyword in python:

The `break` keyword is used to stop the iteration process in python.

The iteration process can end when the keyword "break" appears automatically while iterating the list of items. 

check this example for better understanding

### Example:
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
In this example student_list have four students but we got output only two members from list,

In this example, the "break" keyword is used to stop the iteration process. Here, the keyword is performed as the third student name is printed, stopping the process, and printing only the second item of the list. 

## `continue` keyword in python:

In a for loop (or a while loop), the continue keyword is used to end the current iteration and go on to the next one. 

The `continue` keyword can continue the iteration process it is completly opposite to break keyword in python.

### Example:
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

## `else` keyword in python:

The `else` keyword is a control flow and iteration keyword in python.

### Example: for 'else' keyword
```python
x = 55
if x > 60:
  print("YES")
else:
  print("NO") 
```
output:
```python
NO
```
In this Example 'x is 55' next if condition is 'x is greater than 60' condition is 'not satisfied' and it jump to else condition and execute this 'else' condition and give output as 'NO'.

## Summary
In this tutorial we learnt about Python `iteration keywords` usage and examples in detail.