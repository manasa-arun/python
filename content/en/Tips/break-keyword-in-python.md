---
title: "Python 'break' keyword usage,examples"
description: "The 'break' keyword is one of the keyword out of thirty-five keywords in Python."
date: "2022-09-09T8:30:05+09:00"
draft: false
link: "'break' keyword"
author: "harika"
---


## Python `break` keyword 

1. The`break` keyword is one of the keyword out of thirty-five keywords in Python.

2. The `break` keyword is used to stop the iteration process in Python.

3. The iteration process can end when the keyword `break` appears automatically while iterating the list of items. 

## Python `break` keyword  Uses

1. In Python, the `break` keyword is used to exit a loop early, before the loop condition is false. 

2. It is often used within the body of a looping structure, such as a for loop or a while loop.

## Python `break` keyword  Syntax

```Python
Loop{
    Condition:
        break
    }
```
## Python `break` keyword Examples:

let's go through some of examples to understand `break` keyword in Python.

### Example 1:
In this example student_list have four students but we got output only two members from list,how it is possible lets see

```Python
students_list = ["aaaa", "bbbb", "cccc","dddd"]
for x in students_list:
    if x == "cccc":
        break
    print(x)
```
output:
```Python
aaaa
bbbb
```
In this example, the `break` keyword is used to stop the iteration process. Here, the keyword is performed as the third student name is printed, stopping the process, and printing only the second item of the list, so only first two students name can be entered here.

### Example 2:
using `break` keyword in for loop

```Python
for i in range(10):
    print(i)
    if i == 5:
        break
```

output:
```Python
0
1
2
3
4
5
```

### Example 3:
program to find first 3 multiples of 6, using break keyword in `while` loop

```Python
# program to find first 3 multiples of 6

i = 1

while (i<=10):
    print('6 * ',(i), '=',6 * i)

    if i >= 3:
        break
    
    i = i + 1
```

output:
```Python
6 *  1 = 6
6 *  2 = 12
6 *  3 = 18
```

## Summary
In this tutorial we learnt about Python `break` keyword usage with the help of simple examples.
