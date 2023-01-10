---
title: "control flow  keywords in Python"
description: "if, elif, else keywords in detail"
date: "2022-09-08T11:30:05+09:00"
draft: false
link: "Python control flow keywords"
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

# control flow keywords:
control keywords include three of the Thirty-five  total keywords. 
if,elif,else these three are the control flow keywords in Python.
variable name doesn't match with these keywords.

# if, else keywords:
You can only run a block of code if a condition is True by using the `if` keyword to create conditional statements (also known as if statements).
To run code if the condition is False, use the `else` keyword.

# Example:1 for 'if' keyword
```Python
even_numbers = [0,2,4,6,8]

if 4 in even_numbers:
    print("it is an even number")
else:
    print("it is a odd number")
```
# output:
```
it is an even number
```

In this example1 '4' is an even number so if condition satisfied then if condition block executed and give out put as 'it is an even number'

 'NO'
# Example:2 for 'else' keyword
```
x = 55
if x > 60:
  print("YES")
else:
  print("NO") 
```
# output:
```
NO
```
In this Example 'x is 55' next if condition is 'x is greater than 60' condition is 'not satisfied' and it jump to else condition and execute this 'else' condition and give output as 'NO'.
# elif keyword in Python:
The 'elif' is a control keyword in Python.

The Elif is a term that stands for "else if" and can be used to prevent using too much indentation.

An alternative to switch or case statements common in other languages is an if... elif... elif... sequence.

# Example:
```Python
a=10
b=6
c= a+b
if c%2 == 0:
    print("c is a even number")
elif c%2 != 0:
    print("c is a odd number")
```

output:

```Python
c is a even number
```

In this example a,b values given, the next step  c condition is to sum the values of a and b. .

then C examines the if condition, such as if 'c is divided by 2'and the result is '0', then c is an 'even number'. 

In some cases if condition is not satisfied then it jump to 'elif' keyword condition and C examines the elif condition, such as 'elif' c is divided by 2'and the result is '!=0', then c is an 'odd number'.

