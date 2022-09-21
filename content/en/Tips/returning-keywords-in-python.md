---
title: "returning keywords in python"
description: " return, yield keywords in detail"
date: "2022-09-21T02:10:05+09:00"
draft: false
link: "python returning keywords"
author: "harika"
---

# introduction to keywords:
Keywords are python reserved words.
We cannot use them as constants or variables or any other identifier names.

## list of Thirty-five keywords in python:
we can list out keywords with `help()` 
```
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

# returning keywords in python:
return, yield keywords re returning keywords in python.

# yield keyword in python:
The `yield ` keyword means provide output as continue, means the programing code can `continue` to the next part of execution.

The `yield` gives a generator object.
It is used inside the function.
It keeps the states of local variable.
I does not exit the function

# Example:
```
# welcome to Pythonshiksha
# program for yield keyword 

def my_list(num):
    for i in range(num):
        print('local variable i:', i)
        yield i

print(my_list(5))
print(list(my_list(5)))
```
# output:
```
<generator object my_list at 0x006C4680>
local variable i: 0
local variable i: 1
local variable i: 2
local variable i: 3
local variable i: 4
[0, 1, 2, 3, 4]
```
`yield` keyword can help continue the iteration to get the output.

# return keyword in python:
The `return ` keyword means provide output as stop, means the programing code can `stop` there and it will not go to the next part of execution

The `yield` gives back the actual returned value.
It is used inside the function.
It destroys the states of local variable.
It exits the function.

The `yield` keyword pauses generator function execution and the value of the expression following the yield keyword is returned to the generator's caller.

# Example:
```
# welcome to Pythonshiksha
# program for return keyword usage

def my_list(num):
    for i in range(num):
        print('local variable i:', i)
        return i

print(my_list(5))
```
# output:
```
local variable i: 0
0
```
In this program `return` keyword is used so it gives the original value and exists the function, so for loop iterated only once and give output only one local variable.



