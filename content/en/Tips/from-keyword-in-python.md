---
title: "from keywords in python"
description: " The `from` keyword is one of the keyword out of thirty-five keywords in python"
date: "2022-09-20T12:10:05+09:00"
draft: false
link: "python from keywords"
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

## `from` keyword in python

1. The `from` keyword is one of the keyword out of thirty-five keywords in python.

2. In Python, there are many different modules that may be imported. The `from` keyword can be used to choose a specific method from any module and then utilize it. 


## `from` keyword syntax in python

```python
from <module> import <thing>
```

### `from()` keyword Examples:

let's go through some of examples to understand `from()` keyword in python

### Example 1:

```python
from datetime import time

x = time(hour=18)

print(x)
```
output:

```python
18:00:00
```
In python datetime is a module in that we can select only hour from the datetime module in this case `from` key word is used like this.

### Example 2:

```python
from sys import version

print(version)
```
output:

```python
3.8.8 (default, Apr 13 2021, 15:08:07) [MSC v.1916 32 bit (Intel)]
```

## Summary
In this tutorial we learnt about Python `from` keyword usage and examples to better understand.