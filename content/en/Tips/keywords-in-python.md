---
title: "keywords in python"
description: "Keywords are python reserved words"
date: "2022-09-06T11:25:05+09:00"
draft: false
link: "python keywords"
author: "harika"
---

## introduction to `keywords` in python

Keywords are python reserved words.
We cannot use them as constants or variables or any other identifier names.

## list of Thirty-five `keywords` in python:

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

### Example: let's try with another keyword  `lambda`

```python
>>> help("lambda")
Lambdas
*******

   lambda_expr        ::= "lambda" [parameter_list] ":" expression
   lambda_expr_nocond ::= "lambda" [parameter_list] ":" expression_nocond

Lambda expressions (sometimes called lambda forms) are used to create
anonymous functions. The expression "lambda parameters: expression"
yields a function object.  The unnamed object behaves like a function
object defined with:

   def <lambda>(parameters):
       return expression

See section Function definitions for the syntax of parameter lists.
Note that functions created with lambda expressions cannot contain
statements or annotations.

Related help topics: FUNCTIONS
```

## `keywords types` in python:

According to their usage of keywords,they can divided in to these 7 types.
   
1. Value Keywords: True, False, None.
2. Operator Keywords: and, or, not, in, is.
3. Control Flow Keywords: if, elif, else.
4. Iteration Keywords: for, while, break, continue, else.
5. Structure Keywords: def, class, with, as, pass, lambda.
6. Returning Keywords: return, yield.
7. Import Keywords: import, from, as.

Keyword 	          Description

and	              A logical operator
as	                 To create an alias
assert	           For debugging
break	              To break out of a loop
class	              To define a class
continue	           To continue to the next iteration of a loop
def	              To define a function
del	              To delete an object
elif	              Used in conditional statements, same as else if
else	              Used in conditional statements
except	           Used with exceptions, what to do when an exception occurs
False	              Boolean value, result of comparison operations
finally	           Used with exceptions
for	              To create a for loop
from	              To import specific parts of a module
global	           To declare a global variable
if	                 To make a conditional statement
import	           To import a module
in       	        To check if a value is present in a list, tuple, etc.
is	                 To test if two variables are equal
lambda   	        To create an anonymous function
None	              Represents a null value
nonlocal	           To declare a non-local variable
not	              A logical operator
or	                 A logical operator
pass	              A null statement, a statement that will do nothing
raise	              To raise an exception
return	           To exit a function and return a value
True	              Boolean value, result of comparison operations
try	              To make a try...except statement
while	              To create a while loop
with	              Used to simplify exception handling
yield	              To end a function, returns a generator

## Summary
In this tutorial we learnt about Python `keywords` and `keywords types ` in detail.