---

title: "python create list with numbers between 2 values"
description: " range function can use to create list with numbers between 2 values in python"
date: "2022-04-29 T010:32:05+09:00"
draft: false
link: "strings"
author: "harika"
---
## introduction:
`List` is a compound data type in python. list is a set of values of different data types.

list values separated with , and enclosed with in square brackets([]).

my_list =[saanvi,29,4.8,-4,]

here my_list is created with different data types.

## create list with numbers between 2 values:

## using range():

Range function in python is use to generate a list, which
Is special sequence type.

We can pass two parameters to this `range()`function.
1.lower limit
2.upper limit

range(lower limit,upper limit)
list creation is starts with lower limit and ends with upper limit.

range(lower limit,upper limit,step)

here `step` is a number added with lower limit and forward to next number until it reaches the upper limit.

list() can use to convert sequence numbers in python list.

**Example**:
```
num_list = range(5,10)   ## numbers in range
my_list = list(num_list) ## numbers list is converted in to list
print(my_list)           ## print list here
```
output:
```
[5, 6, 7, 8, 9]
```
we got a output  with 5,6,7,8,9 why because 5 is the lower limit and 10 is the upper limit, the range function sequence begins with 5 and finishes with 10.

In this, 5 is automatically increased to 1; that is, 5 is added to 1 and the next number is 6, 

if we not mentioned `step` value just as 1 is automatically added to the lower limit, until it reaches the upper limit 

Another example to range function
**Example**
```
num_list = range(5,10,2)   ## numbers in range
my_list = list(num_list) ## numbers list is converted in to list
print(my_list)           ## print list here
```
output:
```
[5, 7, 9]
```

in this example step value is added 2 so the lower limit number increased to step value that is 2 so 

5 added 2 next value 7
7 added 2 next value 9
9 added 2 next value 11 but in output 11 is not displayed why because upper limit is 10 only.

like this we can easily create a list in python with two values.

**Example**

In step value we cam use negative values like this.
```
num_list = range(5,10,-1)   ## numbers in range
my_list = list(num_list) ## numbers list is converted in to list
print(my_list)           ## print list here
```
output:
```
[10,9,8,7,6]
```
Note: Negative values in step values can be used to create a descending order list.

## conclusion:
using range() we can easily create a list with 2 values in python,

in this article we explained in a simple python program code with best example you can also try your own list.
