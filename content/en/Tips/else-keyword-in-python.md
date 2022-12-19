---
title: "Python 'else' keyword usage, examples"
description: "The 'else' keyword is one of the keyword out of thirty-five keywords in python"
date: "2022-09-09T8:30:05+09:00"
draft: false
link: "'else' keyword"
author: "harika"
---

## python`else` keyword

1. The`else` keyword is one of the keyword out of thirty-five keywords in python.

2. The `else` keyword is iteration type of keyword in python.

3. The `else` keyword is a control flow and iteration keyword in python.

4. The `if` block condition is not satisfied then `else` block condition will executes.

## python `else` keyword Uses

The `else` keyword in Python is used in several contexts. 
1. for loop
2. while loop
3. if statement

## python `else` keyword Syntax 

```python
if test_condition:
	    statement(s)-true
    else:
	    statement(s)-false
```

## python `else` keyword Examples:

let's go through some of examples to understand `else` keyword in python

### Example 1:
checking the number is small or big using `else` keyword. if condition is not satisfied then `else` block will execute.

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
In this Example 'x is 55',
`if condition` is '55 is not greater than 60' so the condition is 'not satisfied' and it jump to `else` condition and execute this `else` condition and give output as `NO`.


### Example 2: comparing numbers using `else` keyword in while loop

```python
num1 = input("Enter a number: ")
num2 = input("Enter another number:")

# comparing numbers 
while num1> num2:
    print("num1 is small")
else:
    print("num 2 is big")
```
output:

```python
Enter a number: 22
Enter another number:23
num 2 is big
```
here `num1 is 22`, `num2 is 23` so if (22>23)condition is not satisfied then `else` statement can executed as `num2 is big`

### Example 3:
Using `else` keyword in for loop

```python
for x in range(3):
    print ("iteration no {} in for loop".format(x+1))
else:
    print ("else block in loop")
print ("Out of loop")
```
output
```python
iteration no 1 in for loop
iteration no 2 in for loop
iteration no 3 in for loop
else block in loop
Out of loop
```

## Summary
In this tutorial we learnt about Python `else` keyword usage with the help of simple examples.

