---
title: "structure keywords in python"
description: " def, class, with, as, pass, lambda keywords in detail"
date: "2022-09-09T8:30:05+09:00"
draft: false
link: "python structure keywords"
author: "harika"
---

# introduction to keywords:
Keywords are python reserved words.
We cannot use them as constants or variables or any other identifier names.

## list of Thirty-five keywords in python:
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

# structure  keywords in python:
structure keywords include six of the Thirty-five  total keywords.
 def, class, with, as, pass, lambda keywords are iteration keywords.

# def keyword in python:
Python def keyword is used to define a function, it is placed before a function name that is provided by the user to create a user-defined function. 

# syntax:
```
def function name:
    statements
```
with out `def` keyword we can not create a user defined or any function.

# Example:
```
def add(x,y):
  return x+y

def mul(x,y):
  return x*y

def sub(x,y):
  return x-y
a=10
b=6

print('sum=', add(a,b))
print('mul=', mul(a,b))
print('sub=', sub(a,b))
```
# output:
```
sum= 16
mul= 60
sub= 4
```

# pass keyword in python:
The `pass` is nothing.
The `pass` keyword is written as there should be a statement for if.
The output as "End of program"

# Example:
```
if 3==3:
  pass
print("end of program")
```
# output:
```
end of program
```
# class keyword in python:
A `class` is a collection of data attributes and methods for a specific 
objects.
# syntax of class:
```
class class_name:
     members
```
After creating the objects, we can involve methods of that class with.(dot)

# Example:
```
class student:
  def setdata(self,name,rno):
    self._name = name
    self._rno =rno

  def showdata(self):
    print('Name:', self._name)
    print('rno:', self._rno)
  
  s1 = student
  s1.setdata("Aaaa", 25)
  s1.showdata()
```
# output:
```
Name: Aaaa
rno:25
```
# lambda keyword in python:
Small anonymous functions are created with the `lambda` keyword.

A lambda function can have one expression but any number of arguments.

The result of evaluating the expression is returned. 

# Syntax of lambda:
```
lambda arguments: expression
```
anonymous means the function don't have a name for it, these type of functions are created with this `lambda` keyword only.

# Example:
```
x = lambda a, b, c : a + b + c

print(x(7, 9, 15)) 
```
Verify this Example.
Multiple attributes are allowed here, and lambda has no function name and an expression that only spans one line. 

# with keyword in python:
The advantage of using 'with' keyword in program it is automatically close the file with out any using close operation in it.

# Example: with out using `with` keyword
```
fw = open("demo.txt","w")
fw.write("pythonshiksha")
# fw.close()

fr = open("demo.txt","r")
print(fr.read())
```
# output:
```
nothing will display here 
```
Without closing the demo file first, this program cannot read the file again since the close procedure is missing from it. 

# Example:
```
fw = open("demo.txt","w")
fw.write("pythonshiksha")
fw.close()

fr = open("demo.txt","r")
print(fr.read())
```
# oputput:
```
pythonshiksha
```
When a file is opened in this programme, it will be closed using a close operation before being read again and producing an output like 
"pythonshiksha." 

To avoid making these errors, we can utilise the "with" keyword and perform any activities there; we don't need to explicitly tell the programme to close after each operation. 

# syntax of with keyword:
```
with expression [as variable]:
    with-block
```

check this example for better understanding.

# Example: using with keyword
```
with open("demo.txt","w") as fw:
    fw.write("example for with keyword")

with open("demo.txt","r") as fr:
    print(fr.read())
```
# output:
```
example for with keyword
```
In this example after writing the program also we can not use close the file here,