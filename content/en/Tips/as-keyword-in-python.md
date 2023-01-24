---
title: "Python 'as' keyword usage,examples"
description: "The 'as' keyword is one of the keyword out of thirty-five keywords in Python"
date: "2022-09-20T12:10:05+09:00"
draft: false
link: "'as' keyword"
author: "harika"
---

## Python`as` keyword 

1. The `as` keyword is one of the keyword out of thirty-five keywords in Python
2. The `as` keyword is used to alias an imported module or tool.
3. Instead of using whole name of the particular objects or modules we can rename with simple letters w,r like
w for write
r for read

## Python`as` keyword Uses

1. The `as` keyword can be used in an import statement to give a module or package a different alias. 
2. This can be useful if the module or package has a long or cumbersome name, or if the name conflicts with another name in your code.

## Python`as` keyword syntax 

```Python
import <module> as <alias>
from <module> import <thing> as <alias>
```

## Python `as` keyword Examples:

let's go through some of examples to understand `as` keyword in Python

### Example 1:
reopen,rewrite a file using `as`keyword

```Python
with open("demo.txt","w") as fw:
    fw.write("Best Python learning tutorial- PYTHONSHIKSHA")
with open("demo.txt","r") as fr:
    print(fr.read())
```
output:

```Python
Best Python learning tutorial- PYTHONSHIKSHA
```

### Example 2:
print random numbers using `as` keyword

```Python
import random as rnd

for i in range(5):
    print (rnd.randint(0, 5), end=" ")

print()
```

output:

```Python
1 1 5 0 1
```
every time while executing this code output must be not same.
we can get random integers from 0 to 5.

## Summary
In this tutorial we learnt about Python `as` keyword usage with the help of simple examples.
