---
title: "Absolute value in python"
description: "Defining the absolute value in python"
date: "2022-06-27T11:20:05+09:00"
draft: false
link: "Absolute value in python"
author: "harika"
---

## introduction to absolute value:

absolute values commonly used in school syllabus like mathematics,physics,engineering subjects also this knowledge is enough to learn this concept in python.

The absolute value of a number in any programming language is the value without regard to its sign. 

We use Python’s abs() built-in function to return an absolute value of any numeric input passed as an argument to the function.

It converts all numeric numbers to positive (or zero).

# Syntax:
```
abs(num)
```
where number is a integer number, or float number,or complex number
it takes single parameter

# Return value from abs():

The python abs() function returns the absolute value of the passed number.

For integers as inputs – an integer absolute value is returned
Example:
(integer) absolute value of -4 = 4
|-4|= 4 or |4|=4

For floating-point numbers as inputs – a floating absolute value number is returned
Example:
(float number)absolute value of -12.5= 12.5
|-12.5|= 12.5 or |12.5|= 12.5

If the inputs are complex numbers – the magnitude of the complex numbers is returned. 
Example:
Complex number = a+bj, Magnitude = √(a2+b2)
|3+2j|= √3^2+2^2 
      = √9+4
      = √13
      = 3.6055

so |3+2j| absolute number is 3.6055     
|-(3+2j)| absolute number is 3.6055 

let us understand this concept in python programs 
# Example:
```
# To find any type of absolute value here
x =-25
y = 25
if x>0:
    print(x)
else:
    print(0-x)

print(abs(y))
```
# output:
```
25
25
```
# Example:
To find absolute value for any integer value here
```
#To find integer absolute value here
mynum1 = 10
mynum2 =-10
print('Absolute value of 10 is:', abs(mynum1))
print('Absolute value of 10 is:', abs(mynum2))
```
# output:
```
Absolute value of 10 is: 10
Absolute value of 10 is: 10
```
# Example:
program for floating type absolute value
```
#To find float type absolute value here
mynum1 = 20.5
mynum2 =-20.5
print('Absolute value of 10 is:', abs(mynum1))
print('Absolute value of 10 is:', abs(mynum2 ))
```
# output:
```
Absolute value of 10 is: 20.5
Absolute value of 10 is: 20.5
```
# Example:
```
#To find complex number absolute value here
mynum1 = 5+3j
mynum2 =-(5+3j)
print('Absolute value of 10 is:', abs(mynum1))
print('Absolute value of 10 is:', abs(mynum2 ))
```
# output:
```
Absolute value of 10 is: 5.830951894845301
Absolute value of 10 is: 5.830951894845301
```
where complex number 5+3j in that 5 is real number and 3 is imaginary number











                


