---
title: "vars built-in function in python"
description: "vars built in functions in python"
date: "2022-08-18T11:50:05+09:00"
draft: false
link: "vars() Built-in functions"
author: "harika"
---

## vars() function in python:
The `vars()` function is a one of the built-in functions in python.
`vars()` is used for	`Returns the __dict__ property of an object`.

# syntax:
```
vars(object)
```
where, 
object is  can be a module, class, instance, or any object having the __dict__ attribute

The vars() method returns:

__dict__ attribute of the given object.
methods in the local scope when no arguments are passed
TypeError if the object passed doesn't have the __dict__ attribute


# Example: 1
```
class student:
  def __init__(self, telugu= 85, hindi= 80, english=67,maths= 90,science =89, social =77):
    self.telugu = telugu
    self.hindi = hindi
    self.english = english
    self.maths = maths
    self.science = science
    self.social = social
  
subjects = student()

# returns __dict__ of the student object
print(vars(subjects))
```
# output:
```
{'telugu': 85, 'hindi': 80, 'english': 67, 'maths': 90, 'science': 89, 'social': 77}
```
# Example:2
```
# vars() with no argument
print (vars())

```
# output:
```
{'__name__': '__main__', '__doc__': None, '__package__': None, '__loader__': <_frozen_importlib_external.SourceFileLoader object at 0x003AF838>, '__spec__': None, '__annotations__': {}, '__builtins__': <module 'builtins' (built-in)>, '__file__': 'c:/Users/Vamshi/date string.py', '__cached__': None'}

```


