---
title: "pass keyword in python"
description: " The `pass` keyword is one of the keyword out of thirty-five keywords in python"
date: "2022-09-20T11:00:05+09:00"
draft: false
link: "python pass keyword"
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

## `pass` keyword in python:

1. The `pass` keyword is one of the keyword out of thirty-five keywords in python.
2. The `pass` is nothing.
3. The `pass` keyword is written as there should be a statement for if.
The output as "End of program"
4. Empty code is not allowed in loops, function definitions, class definitions, or in if statements.


### `pass()` keyword Examples:

let's go through some of examples to understand `pass()` keyword in python

### Example 1:

```python
if 3==3:
  pass
print("end of program")
```
output:

```python
end of program
```
### Example 2:

```python
def mynum():
  pass
```

output:
```
```
nothing will display here.
having an empty function definition like this, would raise an error without the pass statement
 

## Summary
In this tutorial we learnt about Python `pass` keyword usage and examples to better understand.