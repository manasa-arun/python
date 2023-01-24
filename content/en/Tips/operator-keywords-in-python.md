---
title: "operator keywords in Python"
description: "and,or,not,in, keywords in detail"
date: "2022-09-07T12:00:05+09:00"
draft: false
link: "Python operator keywords"
author: "harika"
---

# introduction to keywords:
Keywords are Python reserved words.
We cannot use them as constants or variables or any other identifier names.

## list of Thirty-five keywords in Python:
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
# operator keywords in Python:
Operator keywords include four of the Thirty-five  total keywords. 
and, or, not, in, is these are the operator keywords in Python.
variable name doesn't match ith these keywords.


# and keyword in Python:
Python `and` is a logical operator
when we want to compare two different conditions we can use this `and` operator like this

# Example:
```
a = 25
b = 40
c = 30

print(a>b and c>a)
print(a<=c and b>=c)
print(c==30 and b==20) 
print(a<30 and b>35) 
```
# output:
```
False
True
False
True
```
in this example a,b,c are variables hen we want apply conditions to it or when we ant to compare e can use `and ` keyword like this

check the two conditions and if conditions is satisfied it will give output as `True or False` according to condition.


# or keyword in Python:
Python `or` keyword is a logical operator

Python OR Keyword Truth Table
Input 1  	  Input2	         Output
True	      True	         True
True	      False	         True
False	      True	         True
False	      False	         False

# Or Truth table can work like this if :

condition 1 is True `or` condition2 is True  then it ill give output as `True`
condition 1 is True `or` condition2 is False  then it ill give output as `True`
condition 1 is False `or` condition2 is True  then it ill give output as `True`
condition 1 is False `or` condition2 is False  then it ill give output as `False`

# Example:
```
i = 0
a = 'Pythonshiksha'
  
while i < len(a):
    if a[i] == 'e' or a[i] == 'k':
        i += 1
        break
  
    print('Current Letter :', a[i])
    i += 1
```
# output:
```
Current Letter : p
Current Letter : y
Current Letter : t
Current Letter : h
Current Letter : o
Current Letter : n
Current Letter : s
Current Letter : h
Current Letter : i
```
In this example a[i]= 'k'  so it will display before k letters in 'Pythonshiksha'.

# Example:
if a[i]= 'y' now the output will be like this

```
i = 0
a = 'Pythonshiksha'
  
while i < len(a):
    if a[i] == 'e' or a[i] == 'y':
        i += 1
        break
  
    print('Current Letter :', a[i])
    i += 1

```
# output:
```
Current Letter : p
```
here we got output only p why because now a[i] is y so before y letters can display in Pythonshiksha word.

# not keyword in Python:
The 'not' keyword is a logical operator.

The return value will be 'True' if the statement(s) are not 'True', otherwise it will return 'False'.

# Example:
```
a = 5
print(a>1, not a)
```
# Output:
```
True False
```

In this Example a is 5 
a is bigger than 1 so it is 'True'
the condition is 'True' not keyword can give output as 'False'.
so output will be 'True False'

# in keyword in Python:
The `in` is a membership operator in Python.
The `in` keyword has two purposes:

The `in` keyword is used to check if a value is present in a sequence (list, range, string etc.).

The`in` keyword is also used to iterate through a sequence in a for loop:

# Example:
```
vowels = ["a","e","i","o","u"]

if "c" in vowels:
    print("yes")
else:
    print("no")
```
# output:
```
no
```
In this example 'c' is not there in 'vowels' so output is 'no'

# Example:
```
best_tutorial = "Pythonshiksha"
 
# Iterating through the string
for i in best_tutorial:
     # break the loop
    if i == 'f':
        break
     
    print(i)
```
# output:
```
p
y
t
h
o
n
s
h
i
k
s
h
a
```
here i is f now in 'Pythonshiksha' word 'f' letter is not there so it will display all the letters in it.

