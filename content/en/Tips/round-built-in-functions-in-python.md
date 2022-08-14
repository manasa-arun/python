---
title: "round built-in function in python"
description: "round built in functions in python"
date: "2022-08-06T05:50:05+09:00"
draft: false
link: "round() Built-in functions"
author: "harika"
---

## round() function in python:
The `round()` function is a one of the built-in functions in python.
`round()` is used for `Rounds a numbers`.


## Syntax:
```
round(number, digits)
```
where,
number is Required-The number to be rounded
digits is Optional-The number of decimals to use when rounding the number. Default is 0

If the second parameter is missing, then the round() function returns: 

if only an integer is given, for instance 15, then it will round off to 15 itself.

if a decimal number is given, then it will round off to the closest multiple of 10 to the power minus ndigits


## Example:
```
#Round to the nearest integer:
num = round(31.2924)
print(num) 
```
output:
```
31
```
here digit is '0'so output will be nearest number to decimal number 

## Example: 2
```
#Round to the nearest integer:
num = round(31.2924,1)
print(num) 

print(round(31.2924,2))
print(round(31.2924,3))
print(round(31.2924,4))
print(round(31.2924,5))
```
output:
```
31.3
31.29
31.292
31.2924
31.2924
```
# Example:
```
#Round to the nearest integer:

print(round(31.4924))
print(round(31.5924,3))
print(round(31.5924))
print(round(31.6924,4))
print(round(31.6924))
```
output:
```
31
31.592
32
31.6924
32
```

