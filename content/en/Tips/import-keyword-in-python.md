---
title: "import keyword in Python"
description: " The 'import' keyword is one of the keyword out of thirty-five keywords in Python"
date: "2022-09-20T12:10:05+09:00"
draft: false
link: "Python import keyword"
author: "harika"
---

## introduction to keywords:
Keywords are Python reserved words.
We cannot use them as constants or variables or any other identifier names.

## list of Thirty-five keywords in Python:
we can list out keywords with `help()` 

```Python
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

## Import keywords in Python:

`import,as,from` keywords are import keywords in Python.


## import in Python:
1. The `import` keyword is one of the keyword out of thirty-five keywords in Python"
2. The `import` keyword is used to import the modules
3. In Python Modules cannot be used without being imported first.

## `import` keyword in Python:

```Python
import <module>
```

### `import()` keyword Examples:

let's go through some of examples to understand `import()` keyword in Python

### Example 1:

```Python
import datetime

x = datetime.datetime.now()

print(x)
```
output:

```Python
2022-09-20 05:58:30.738629
```
### Example 2:

```Python
import math
x=math.sqrt(25)
print(x)
print(math.sqrt(100))
print(math.sqrt(200))
```
output:

```Python
5.0
10.0
14.142135623730951
```

## Summary
In this tutorial we learnt about Python `import` keyword usage and examples to better understand.