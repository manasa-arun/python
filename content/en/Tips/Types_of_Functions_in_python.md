---
title: "Types of functions in python"
description: "Two important types in functions in python"
date: "2022-06-24T04:15:05+09:00"
draft: false
link: "functions"
author: "harika"
---

## introduction of Functions:
A function is a group statements that exist within a program for the purpose of performing a specific task and it will be executed only when it is called.
## Syantax:
```
>>> def function_name():
	statements
```
## Types of Functions:
Functions are mainly two types in python
1.Predefined functions
2.user defined functions

## 1.Predefined Functions:
Predefined Functions is also call as `Built-in Functions`.

Python built-in functions are functions that have pre-defined functionality in Python.

The Python interpreter has a number of functions that are always available for use.

Python has several built-in functions, which are listed below: 

There are 68 Built in Functions are there in python.

1.`chr()`is used for `Returns a character from the specified Unicode code`.

2.`classmethod()` is usd for	`Converts a method into a class method`

3.`compile()` is used for `Returns the specified source as an object`, ready to be executed

4.`complex()` is used for `Returns a complex number`.

5.`delattr()` is used for `Deletes the specified attribute`(property or method) from the specified object.

6.`dict()`is used for `Returns a dictionary (Array)`.

7.`dir()` is used for `Returns a list of the specified object's properties and methods`.

8.`divmod()` is usd for	`Returns the quotient and the remainder when argument1 is divided by argument2`

9.`enumerate()` is used for `Takes a collection (e.g. a tuple) and returns it as an enumerate object`.

10.`eval()` is used for	`Evaluates and executes an expression`.

11.`exec()`is used for	`Executes the specified code (or object)`.

12.`filter()` is used for `Use a filter function to exclude items in an iterable object`.

13.`float()` is used for `Returns a floating point number`.

14.`abs()` is used for `Returns the absolute value of a number`.

15.`all()` is used for `Returns True if all items in an iterable object are true`

16.`any()` is used for	`Returns True if any item in an iterable object is true`.

17.`ascii()` is used for `Returns a readable version of an object`. Replaces none-ascii characters with escape character

18.`bin()` is used for	`Returns the binary version of a number`.

19.`bool()` is used for	`Returns the boolean value of the specified object`.

20.`bytearray()` is used for `Returns an array of bytes`.

21.`bytes()` is used for `Returns a bytes object`.

22.`callable()` is used for `Returns True if the specified object is callable, otherwise False`.

23.`list()` is used for `Returns a list`.

24.`locals()` is used for `Returns an updated dictionary of the current local symbol table`.

25.`map()` is used for	`Returns the specified iterator with the specified function applied to each item`.

26.`max()` is used for	`Returns the largest item in an iterable`.

27.`memoryview()` is used for `Returns a memory view object`.

28.`min()` is used for	`Returns the smallest item in an iterable`.

29.`next()` is used for `Returns the next item in an iterable`.

30.`object()` is used for	`Returns a new object`.

31.`oct()` is used for	`Converts a number into an octal`.

32.`open()` is used for `Opens a file and returns a file object`.

33.`ord()` is usd for `Convert an integer representing the Unicode of the specified character`.

34.`pow()` is used for 	`Returns the value of x to the power of y`.

35.`print()` is used for `Prints to the standard output device`.

36.`property()` is used for Gets, sets, `deletes a property`.

37.`range()` is usd for `Returns a sequence of numbers`, starting from 0 and increments by 1 (by default).

38.`repr()`is used for `Returns a readable version of an object`.

39.`reversed()` is usd for `Returns a reversed iterator`.

40.`round()` is used for `Rounds a numbers`.

41.`set()` is used for	`Returns a new set object`.

42.`setattr()` is used for `Sets an attribute (property/method) of an object`.

43.`slice()` is used for `Returns a slice object`.

44.`sorted()` is used for`Returns a sorted list`.

45.`staticmethod()` is used for	`Converts a method into a static method`.

46.`str()` is used for	`Returns a string object`.


47.`super()` is used for `Returns an object that represents the parent class`.

48.`tuple()` is used for `Returns a tuple`.

49.`type()` is used for	`Returns the type of an object`.

50.`vars()` is used for	`Returns the __dict__ property of an object`.

51.`zip()` is used for `Returns an iterator, from two or more iterators`.

52.`eval()` is used for	`Evaluates and executes an expression`.

53.`exec()` is used for	`Executes the specified code (or object)`.

54.`format()` is used for `Formats a specified value`.

55.`frozenset()` is used for `Returns a frozenset object`.

56.`getattr()`is used for `Returns the value of the specified attribute (property or method)`.

57.`globals()` i used for `Returns the current global symbol table as a dictionary`.

58.`hasattr()` is used for	`Returns True if the specified object has the specified attribute (property/method)`.

59.`hash()` is used for	`Returns the hash value`of a specified object.

60.`help()` is used for `Executes the built-in help system`.

61.`hex()` is used for	`Converts a number into a hexadecimal value`.

62.`id()` is used for `Returns the id of an object`.

63.`input()` is used for `Allowing user input`.

64.`int()` is used for	`Returns an integer number`.

65.`isinstance()` is used for `Returns True if a specified object is an instance of a specified object`.

66.`issubclass()` is used for `Returns True if a specified class is a subclass of a specified object`.

67.`iter()` is used for `Returns an iterator object`.

68.`len()` is usd for `Returns the length of an object`.


## 2.Userdefined Functions:

User-defined functions are functions that we define ourselves to perform a specific task. 

A function is a block of code that performs a specific task.

**Example:**
```
def greet():
    print("hello i hope you are doing well,")

greet()
```
**output:**
```
hello i hope you are doing well,
```
like this a user can create his own functions to get exact output hat a user can required.




