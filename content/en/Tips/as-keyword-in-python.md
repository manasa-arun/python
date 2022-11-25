---
title: "as keywords in python"
description: " The `as` keyword is one of the keyword out of thirty-five keywords in python"
date: "2022-09-20T12:10:05+09:00"
draft: false
link: "python as keywords"
author: "harika"
---

## introduction to keywords:
Keywords are python reserved words.
We cannot use them as constants or variables or any other identifier names.

## list of Thirty-five keywords in python:
we can list out keywords with `help()` 

```python
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

## Import keywords in python:
`import,as,from` keywords are import keywords in python.

## `as` keyword in python

1. The `as` keyword is one of the keyword out of thirty-five keywords in python
2. The `as` keyword is used to alias an imported module or tool.

3. Instead of using whole name of the particular objects or modules we can rename with simple letters w,r like
w for write
r for read

## `as` keyword syntax in python:

```python
import <module> as <alias>
from <module> import <thing> as <alias>
```

### `as()` keyword Examples:

let's go through some of examples to understand `as()` keyword in python

### Example 1:

```python
with open("demo.txt","w") as fw:
    fw.write("Best python learning tutorial- PYTHONSHIKSHA")
with open("demo.txt","r") as fr:
    print(fr.read())
```
output:

```python
Best python learning tutorial- PYTHONSHIKSHA
```

### Example 2:

```python
import random as rnd

for i in range(5):
    print (rnd.randint(0, 5), end=" ")

print()
```

output:

```python
1 1 5 0 1
```
every time while executing this code output must be not same.
we can get random integers from 0 to 5.

## Summary
In this tutorial we learnt about Python `as` keyword usage and examples to better understand.