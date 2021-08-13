---
title: "Determine the type of a Variable"
description: "Two important methods of determining the type of a variable in Python."
date: "2021-07-19T04:15:05+09:00"
draft: false
link: "Determine type of a Variable"
author: "dmohanty"
---

**Variables** play a very important and major role in programming.

**Variables** are nothing but reserved memory locations that are capable of storing values.

Thus, every time we assign a value to a variable, some of the memory is consumed by the variable.

While Data types are the different categories which  define that what type of value is stored inside a variable, whether it is an integer, a floating-point number or a string etc.

## Data Types in Python:

Python has numerous standard data types that are used to define the operations possible on them and the storage method for each of them.

The commonly used data types in python are:

| Data Type      | Constructor |
 ----------- | ----------- 
| Integer      | int()       |
| Float   | float()        |
| String   | str()        |
| List   | list()        |
| Tuple   | tuple()        |
| Dictionary   | dict()        |
| Set   | set()        |


Example:
```
# Integer
a = 10

# Float
b= 25.56

# String
c="Hello World"

# List
d=[1,2,3,4,5]

# Tuple
e=(12,56)

# Dictionary
f={"India":1, "France":2}

# Set
g={1,2,3,4}

```

## Extracting the type of a variable.

Let's start discussing both the method in detail:

### Using the type() method

Python has a built-in `type()` method , which gives the class type of the variable as an output.

The `type()` method takes in one argument i.e., the variable whose data type is to be determined, and it outputs the class type of the argument.

```
a = 10
b= 25.56
c="Hello World"
d=[1,2,3,4,5]
e=(12,56)
f={"India":1, "France":2}
g={1,2,3,4}

print("The Type is: ", type(a))
print("The Type is: ", type(b))
print("The Type is: ", type(c))
print("The Type is: ", type(d))
print("The Type is: ", type(e))
print("The Type is: ", type(f))
print("The Type is: ", type(g))
```

Output:
```
The Type is:  <class 'int'>
The Type is:  <class 'float'>
The Type is:  <class 'str'>
The Type is:  <class 'list'>
The Type is:  <class 'tuple'>
The Type is:  <class 'dict'>
The Type is:  <class 'set'>
```

We have seen the use of the `type()` method for all the data types. Now let’s hop onto the other method i.e. the `isinstance()` method.

### Using the isinstance() method

`isinstance()` is another in-built Python method which can be used to extract the data type of a variable in python.

The `isinstance()` method takes in two arguments, and returns a Boolean value , according to the condition that if the first argument is an instance of class type of the second argument.

Let’s define it by the help of a code:

```
a = 10
b= 25.56
c="Hello World"
d=[1,2,3,4,5]
e=(12,56)
f={"India":1, "France":2}
g={1,2,3,4}

print("The Type is Integer: ", isinstance(a,int))
print("The Type is String: ", isinstance(b,str))
print("The Type is String: ", isinstance(c,str))
print("The Type is List: ", isinstance(d,list))
print("The Type is Set: ", isinstance(e,set))
print("The Type is Dictionary: ", isinstance(f,dict))
print("The Type is Float: ", isinstance(g,float))
```

Output:
```
The Type is Integer:  True
The Type is String:  False
The Type is String:  True
The Type is List:  True
The Type is Set:  False
The Type is Dictionary:  True
The Type is Float:  False
```

## Difference between type() & isinstance()

Since both the methods are equally useful for getting the desired result, we can use either of the method but we should now look at some of the differences between both these methods.

```
class Parent:
    pass

class Child(Parent):
    pass

x1 = Parent()
print(type(x1))
x2 = Child()
print(type(x2))
```

Output:
```
<class '__main__.Parent'>
<class '__main__.Child'>
```

The `type()` returns a True value only if the **exact class type** matches but the `isinstance()` method return true even if the **superclass type** matches.

```
class Parent:
    pass

class Child(Parent):
    pass

x1 = Parent()

x2 = Child()

print(type(x1) is Child)

print(type(x1) is Parent)

print(isinstance(x2,Child))

print(isinstance(x2,Parent))
```

Output:
```
False
True
True
True
```

It is clearly visible from the above output that,  the `isinstance()` method return **True** if the type matched both the Base and Derived class but the `type()` only returns **True** if the type of the passed-on class type matches. 

Thus, we can conclude that :
We can use `type()` if we want to determine the exact type & 

`isinstance()` if we want to determine the type while considering inheritance.

## Conclusion

In this article, we discussed in detail about the two methods that can be used to extract the Data type of a variable in Python.

We first roughly looked at the different Data types in Python, then we discussed about the `type()` method and how can it be used.

Then we discussed about the `isinstance()` method and lastly we looked at the differences between the two methods when used for a **class object**.






