---
title: "import keywords in python"
description: " import,as,from keywords in detail"
date: "2022-09-20T12:10:05+09:00"
draft: false
link: "python import keywords"
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

# Import keywords in python:
`import,as,from` keywords are import keywords in python.


# import in python:
The `import` keyword is used to import the modules
In Python Modules cannot be used without being imported first.

# Example:
```
import datetime

x = datetime.datetime.now()

print(x)
```
# output:
```
2022-09-20 05:58:30.738629
```
# Example:
```
import math
x=math.sqrt(25)
print(x)
print(math.sqrt(100))
print(math.sqrt(200))
```
# output:
```
5.0
10.0
14.142135623730951
```

# as keyword in python:
The `as` keyword is used to create an alias.

Instead of using whole name of the particular objects or modules we can rename with simple letters w,r like
w for write
r for read

# Example:
```
with open("demo.txt","w") as fw:
    fw.write("Best python learning tutorial- PYTHONSHIKSHA"
with open("demo.txt","r") as fr:
    print(fr.read())
```
# output:
```
Best python learning tutorial- PYTHONSHIKSHA
```
# from keyword in python:
In Python, there are many different modules that may be imported. The from keyword can be used to choose a specific method from any module and then utilise it. 

# Example:
```
from datetime import time

x = time(hour=18)

print(x)
```
# output:
```
18:00:00
```
In python datetime is a module in that we can select only hour from the datetime module in this case `from` key word is used like this.
