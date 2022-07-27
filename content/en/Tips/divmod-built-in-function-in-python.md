---
title: "divmod function in python"
description: "divmod built in functions in python"
date: "2022-07-27T07:11:50+09:00"
draft: false
link: "divmod() built-in functions in python"
author: "harika"
---

## divmod() function:
The `divmod()` function is one of the built-in functions in python.
The divmod() function returns a tuple containing the quotient  and the remainder when argument1 (dividend) is divided by argument2 (divisor).

The `divmod()` is part of python’s standard library which takes two numbers as parameters and gives the quotient and remainder of their division as a tuple. 

It is useful in many mathematical applications like checking for divisibility of numbers and establishing if a number is prime or not.

# syantax:
```
divmod(dividend, divisor)
```
where,
dividend- A Number. The number you want to divide
divisor - A Number. The number you want to divide with

# Example:1
```
# divmod() with integers
print('(25, 24) = ', divmod(25,24))
print('(15, 13) = ', divmod(15, 13))
 
# divmod() with int and Floats
print('(8.0, 3) = ', divmod(8.0, 3))
print('(3, 8.0) = ', divmod(3, 8.0))
```
output:
```
(25, 24) =  (1, 1)
(15, 13) =  (1, 2)
(8.0, 3) =  (2.0, 2.0)
(3, 8.0) =  (0.0, 3.0)
```
# Example:2 reversing a number using divmod
```
num = 2931
pal = 0
while num != 0:
    use = divmod(num, 10)
    dig = use[1]
    pal = pal*10+dig
    num = use[0]
print(pal)
```
output:
```
1392
```
# Checking if Number is Prime

For a prime number the count of zero remainder will be only one as no number other than itself will divide it perfectly. 

If the count of zero remainder is greater than 1 then the number is not prime.

# Example:3
```
num1 = 29
num2 = 33
a = num1
b = num2
# counter the number of remainders with value zero
count = 0
while a != 0:
   q, r = divmod(num1, a)
   a -= 1
   if r == 0:
      count += 1
if count > 2:
   print(num1, 'is not Prime')
else:
   print(num1, 'is Prime')

count = 0
while b != 0:
   q, r = divmod(num2, b)
   b -= 1
   if r == 0:
      count += 1
if count > 2:
   print(num2, 'is not Prime')
else:
   print(num2, 'is Prime')

```
output:
```
29 is prime
33 is not prime
```