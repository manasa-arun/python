---
title: "How to extract numbers from a string in python"
description: "four methods to learn How to extract numbers from a string in python"
date: "2022-05-12T10:11:25+09:00"
draft: false
link: "extracting numbers from string"
author: "harika"
---

## introduction:

Extracting digits or numbers from a string may come up frequently during your coding journey.
Whether you are automating a Python script and want to extract specific numerical figures from a CSV file,
a data scientist who needs to separate complex digits and figures from given patterns, 

a python enthusiast who wants to learn here is the solution with python programing code examples

## List comprehension: using(split, isdigit)

This problem can be solved by using the `split` function to convert a string to a list, 

then the list comprehension to iterate through the list, and the `isdigit` function to extract a digit from a string. 

**Example:**

```
test_string = "Saanvi have 2 apples and 3 mangoes"
  
# printing original string 
print("The original string : " + test_string)
  
# using List comprehension + isdigit() +split()
# getting numbers from string 
res = [int(i) for i in test_string.split() if i.isdigit()]
  
# print result
print("The numbers list is : " + str(res))
```
output:
```
The original string : Saanvi have 2 apples and 3 mangoes
The numbers list is : [2, 3]
```
In this manner, we can obtain numbers from the original string. 

This programme can only work with positive numbers; if we enter negative or float numbers in the original string, they are ignored. 

**lets see another Example:**
```
test_string = "Saanvi have -2 apples and 2.5 mangoes"
  
# printing original string 
print("The original string : " + test_string)
  
# using List comprehension + isdigit() +split()
# getting numbers from string 
res = [int(i) for i in test_string.split() if i.isdigit()]
  
# print result
print("The numbers list is : " + str(res))
```
output:
```
The original string : Saanvi have -2 apples and 2.5 mangoes
The numbers list is : []
```
to avoid this problem we can use reGex function like this

## using reGex function:

To get the list of all numbers in a String, use the regular expression ‘[0-9]+’ with re.findall() method. 

[0-9] represents a regular expression to match a single digit in the string. 

[0-9]+ represents continuous digit sequences of any length.

numbers = re.findall('[0-9]+', str)

**Example:**
```
import re
text = "1 apple, 12 banana, total price:55.30"
pattern ="[0-9]+.?[0-9]*"
print(re.findall(pattern,text))
```
output:
```
['1 ', '12 ', '55.30']
```
finally we got a list of numbers from string float numbers also like this with reGex function.

## Regular Expressions: using "\D"

using  "\D" we can extract numbers from string.

**Example:**
```
import re

string = "Saanvi have 2 apples and 3 mangoes"

print("The original string:", string)

num = re.sub("\D"," ",string)

print("Extract Digits:", num)
```
output:
```
The original string: Saanvi have 2 apples and 3 mangoes
Extract Digits:             2            3
```

## using join() + filter() + isdigit():

The `filter()` function filters the digits detected in string.

`isdigit()` function and `join()` function performs the task of reconstruction of join function.

**Example**
```
# Python program to extract digits from string

string = "saanvi have 2 apples and 3 mangoes"
 
# print original string
print("The original string:",string)

# using join() + filter() + isdigit()
num = ''.join(filter(lambda i: i.isdigit(), string)
print("Extract Digits:", num)
```
output:
```
The original string: saanvi have 2 apples and 3 mangoes
Extract Digits: 23
```
if we want to extract `phone numbers` or any numbers from string also just change the original string like this

`string = "TELANGANA COVID 19 HELPLINE : 104 , 8790005197 "`

then output must be like this

`The original string: TELANGANA COVID 19 HELPLINE : 104 , 8790005197`
`Extract Digits:                 19            104   8790005197`

## conclusion:

In this article we are discussed about `extract numbers from any string` with python programing  code examples of "reGex methods" and "\D" and etc try your own string and extract numbers from string 
