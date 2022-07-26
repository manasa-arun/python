---
title: "property built-in function in python"
description: "property built in functions in python"
date: "2022-07-26 T011:00:40+09:00"
draft: true
link: "property() Built-in functions"
author: "harika"
---

## property() in python:
The `property()` function is one of the built-in function in python.
`property()` is used for Gets, sets, `deletes a property`.

Python `property(`) function returns the object of the property class and it is used to create property of a class. 

# Syntax: 
```
property(fget, fset, fdel, doc)
```
Parameters: 

fget() – used to get the value of attribute
fset() – used to set the value of attribute
fdel() – used to delete the attribute value
doc() – string that contains the documentation (docstring) for the attributPython property() function returns the object of the property class and it is used to create property of a class. 

Return: Returns a property attribute from the given getter, setter and deleter.

# Example:
```
class Alphabet:
    def __init__(self, value):
        self._value = value
 
    # getting the values
    def getValue(self):
        print('welcome')
        return self._value
 
    # setting the values
    def setValue(self, value):
        print('Setting value to ' + value)
        self._value = value
 
    # deleting the values
    def delValue(self):
        print('Deleting value')
        del self._value
 
    value = property(getValue, setValue,
                     delValue, )
 
 
# passing the value
x = Alphabet('pythonshiksha')
print(x.value)
 
x.value = 'python'
 
del x.value
```
output:
```
welcome
pythonshiksha
Setting value to GfG
Deleting value
```

    