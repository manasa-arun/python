---
title: "map built-in function in python"
description: "map built in functions in python"
date: "2022-08-18T03:05:05+09:00"
draft: false
link: "map() Built-in functions"
author: "harika"
---

## map() function in python:
The `map()` function is a one of the built-in functions in python.
`map()` is used for	`Returns the specified iterator with the specified function applied to each item`.

For each item in an iterable, the map() function calls a predefined function.
The object is passed as a parameter to the function. 

# Syntax :
```
map(fun, iter)
```
where,

    fun : It is a function to which map passes each element of given iterable.
    iter : It is a iterable which is to be mapped.

NOTE : You can pass one or more iterable to the map() function.

Returns :

Returns a list of the results after applying the given function  
to each item of a given iterable (list, tuple etc.) 

NOTE : The returned value from map() (map object) then can be passed to functions like list() (to create a list), set() (to create a set) .
 
# Example:
```
def mylist(a, b):
  return a + b

x = map(mylist, ('apple', 'banana', 'cherry'), ('orange', 'lemon', 'pineapple'))

print(x)

#convert the map into a list, for readability:
print(list(x))
```
# output:
```
['appleorange', 'bananalemon', 'cherrypineapple']
```
# Example:
```
num1 = [8, 9, 6]
num2 = [9, 6, 8]

result = map(lambda n1, n2: n1+n2, num1, num2)

print(list(result))
```
# output:
```
[17,15,14]
```


