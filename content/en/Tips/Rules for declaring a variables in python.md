---

title: "Rules for declaring a variables in python"
description: "declaring variables "
date: "2022-06-09 T010:32:05+09:00"
draft: false
link: "variables"
author: "harika"
---

## introduction:

Variables are containers for storing data values,stored data in computers memory.

programs usually store data in the computers memory and perform operations on that data through variables.


## Declaring  a variable:
Variables can be declared by any name or even alphabets like a, aa, abc, x,y etc

Example:
x = 6

where
`x` is a variable name
`6` is value 

here 6 value is stored in x.

we can change the value in x

## Re-declare a Variable:

You can re-declare the variable even after you have declared it once.

>>> x=5
>>> x
5
>>> x=10
>>> x
10

variables are strongly and dynamically typed.

`strong` typing means that the type of a value cannot be changed.
a string containing only digits does not become a number without casting notation.
Every change of type requires an explicit conversion.


## Concatenate Variables:
a is stored data as `python` and b is stored as `is a language` we can combine like this

>>> a='python'
>>> b= ' is a language'
>>> a+b
'python is a language'


`python` string is stored with variable name `a` here

every letter in python have an index value like this 

>>> a[0]
'p'
>>> a[1]
'y'
>>> a[2]
't'
>>> a[3]
'h'
>>> a[4]
'o'
>>> a[5]
'n'
>>> a[6]
Traceback (most recent call last):
  File "<pyshell#77>", line 1, in <module>
    a[6]
IndexError: string index out of range

here a[6] have an error why because string index out of range means python can store 0,1,2,3,4,5 index values only

index values have negative values also check this below examples

>>> a[0]
'p'
>>> a[-1]
'n'
>>> a[-2]
'o'
>>> a[-3]
'h'
>>> a[-4]
't'
>>> a[-5]
'y'

Every character in string has an index value that can be positive or negative. 


## why we need variable?

While writing programing code in Python, we must store data in order to assign values to perform operations such as addition, subtraction, and other arithmetic operations.

Exmaple:

>>> x = 3
>>> y = 4
>>> x+y
7

To perform any arithmetic operation, we must first assign values such as x and y. Try your own values. 

## ASSIGNMENT OPERATORS:
1. `=`   x = 25 Value 25 is assigned to x

>>> x=25
>>>  

so x holds 25 value here.

2. `+=`  x += 25 This is same as x = x + 25
>>> x=25
>>> x+=25
>>> x
50

when x value 25 25 added to 25  then we got a result 50

3. `-= `  x -= 25 Same as x = x – 25
>>> x-=25
>>> x
25
when x is 50,  we get a result like 50-25=25

4. `*=`  x *= 25 This is same as x = x * 25
>>> x*=25
>>> x
625

When x is 25, we get a result like 25*25=625 

5. `/=`  x /= 25 Same as x = x / 25

>>> x/=25
>>> x
25.0

when x is 625, 625 is devided by 25 then we get a result like 25.0

here we got float type number 25.0 

6. `//=` x //= 25 Same as x = x // 25
if we don't  want float number in result
>>> x=625
>>> x//25
25

here we get only 25.

7. `%=`  x %= 626 This is identical to x = x % 25
>>> x=626
>>> x%=25
>>> x
1
where x is 626 is devided by 25 the reminder will be 1

8. `**=` x **= 2 This is same as x = x ** 2
>>> x=50
>>> x**=2
>>> x
2500
when x is 50, 50 multiple by 2times and we get a result like 2500
 
## variable naming rules:

when declaring variables we must follow these rules:

1. we cannot use Python's key words as a variable name.

2. A Variable name can not contain spaces.

a b is not valid
ab is valid

3. The first character must be one of the letters of the alphabet or an underscore(_).


4. After first character we may use any letter or digit or underscore.
num1 and num_ is valid
1num and _num is not valid

5. Uppercase and lowercase characters are distinct.

num and Num is different variable names

## Delete a variable:

You can also delete variable using the command del "variable name
>>> x=6
>>> y=4
>>> del x
>>> x
Traceback (most recent call last):
  File "<pyshell#55>", line 1, in <module>
    x
NameError: name 'x' is not defined

x is deleted here.


## conclusion:

We reviewed how to declare a variable, naming rules for variables with examples, how to remove a variable, and assignment operations with examples in this post to help everyone understand everything in a straightforward way. 










