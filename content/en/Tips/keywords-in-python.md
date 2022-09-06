---
title: "keywords in python"
description: "python keywords in detail"
date: "2022-09-06T11:25:05+09:00"
draft: false
link: "keywords in python"
author: "harika"
---

# introduction to keywords:
Keywords are python reserved words.
We cannot use them as constants or variables or any other identifier names.

## list of Thirty-five keywords in python:
we can list out keywords with `help()` 

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


you can use help() again by passing in the specific keyword that you need more information about. 
let's try ith another keyword for example, with the `lambda`keyword:
```
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

According to their usage of keywords,they can divided in to these 7 types:
   
Value Keywords: True, False, None.
Operator Keywords: and, or, not, in, is.
Control Flow Keywords: if, elif, else.
Iteration Keywords: for, while, break, continue, else.
Structure Keywords: def, class, with, as, pass, lambda.
Returning Keywords: return, yield.
Import Keywords: import, from, as.

Keyword 	Description
and	        A logical operator
as	        To create an alias
assert	    For debugging
break	    To break out of a loop
class	    To define a class
continue	To continue to the next iteration of a loop
def	        To define a function
del	        To delete an object
elif	    Used in conditional statements, same as else if
else	    Used in conditional statements
except	    Used with exceptions, what to do when an exception occurs
False	    Boolean value, result of comparison operations
finally	    Used with exceptions, a block of code that will be executed no matter if there is an exception or not
for	        To create a for loop
from	    To import specific parts of a module
global	    To declare a global variable
if	        To make a conditional statement
import	    To import a module
in       	To check if a value is present in a list, tuple, etc.
is	        To test if two variables are equal
lambda   	To create an anonymous function
None	    Represents a null value
nonlocal	To declare a non-local variable
not	        A logical operator
or	        A logical operator
pass	    A null statement, a statement that will do nothing
raise	    To raise an exception
return	    To exit a function and return a value
True	    Boolean value, result of comparison operations
try	        To make a try...except statement
while	    To create a while loop
with	    Used to simplify exception handling
yield	    To end a function, returns a generator

