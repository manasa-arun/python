---
title: "with keyword in python"
description: " The 'with' keyword is one of the keyword out of thirty-five keywords in python"
date: "2022-09-20T11:00:05+09:00"
draft: false
link: "python with keyword"
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

you can use `help()` again by passing in the specific keyword that you need more information about. 

## structure  keywords in python:
structure keywords include six of the Thirty-five  total keywords.
 def, class, with, as, pass, lambda keywords are iteration keywords.

## `with` keyword in python:

1. The `with` keyword is one of the keyword out of thirty-five keywords in python.
2. The advantage of using `with` keyword in program it is automatically close the file with out any using close operation in it.
3. instead of using whole name of the particular objects we can rename with simple letters w,r like
w for write
r for read
 
## syntax of `with` keyword:

```python
with expression [as variable]:
    with-block
```

### `with()` keyword Examples:

let's go through some of examples to understand `with()` keyword in python

### Example 1: using with keyword

```python
with open("demo.txt","w") as fw:
    fw.write("example for with keyword")

with open("demo.txt","r") as fr:
    print(fr.read())
```

output:

```python
example for with keyword
```
In this example after writing the program also we can not use close the file here.

## Summary
In this tutorial we learnt about Python `with` keyword usage and examples to better understand.