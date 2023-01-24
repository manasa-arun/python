---
title: "variables in Python"
description: "Python variables in detail"
date: "2022-09-05T11:15:05+09:00"
draft: false
link: "variables in Python"
author: "harika"
---

## introduction to variables:
A variable is a name that represents a value stored in the computer's memory.
programs usually store data in the computer's memory and perform operations on that data through variables.

## Example:
a=45
b=20.5
c=a+b

In the above example a,b,c are variables.
We can not use variables without assigning any value to them. 
In Python, variables are strongly and dynamically typed.

## strong typing in Python:
strong typing means that the type of a value can not be changed. 
## example:
a string containing only become a number digits doesn't become a number without casting notation.
Every change of type requires an explicit conversion.

## Dynamic typing in Python:
Dynamic typing means that runtime values have a type,as opposed to static typing where variables have a type.

## How to create a variables:
We can create a variable in Python with assignment statement to create a variable and assign a value.

## Example:
num = 25

## How to declare a variable in Python:
        or
## what are the variable naming rules in Python:

when declaring a variables we must follow these rules:
1.we can not use Python's key words as a variable name.
## Example:
  class,continue,lambda Python have more number of keywords
  these names are not allowed to use as variable name

2.A variable name cannot contain spaces
## Example:
  Studentname is correct format
  Studnt name is not correct(spaces are not allowed in variable name)
3.The first character must be one of the letters of the alphabet or an underscore(_).

## Example:
  _num is correct format
  #num is not correct format(first letter should be _ or any letter in alphabets)
  num is correct format
  3num is not correct (should not begin ith number)
  
4.After the first character we may use the any letter or digit or underscore.
## Example:
  my_num is correct
  num1 is correct 1num is not correct(first letter of variable does't contain digit)

5.Uppercase and lowercase characters are distinct.
## Example:
  variable name `CollegeName` is not same as `collegename` 
  age is not same as Age
  X is not same as x

## Example:
```
x = 30
y = "aaa"
print(x)
print(y)
```
## output:
```
30
aaa
```
in this Example x and y are variables.

