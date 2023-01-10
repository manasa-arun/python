---
title: "'with' keyword in Python usage,examples"
description: " The 'with' keyword is one of the keyword out of thirty-five keywords in Python"
date: "2022-09-20T11:00:05+09:00"
draft: false
link: "'with' keyword"
author: "harika"
---

## Python `with` keyword 

1. The `with` keyword is one of the keyword out of thirty-five keywords in Python.
2. The advantage of using `with` keyword in program it is automatically close the file with out any using close operation in it.
3. instead of using whole name of the particular objects we can rename with simple letters w,r like
w for write
r for read
 
## Python `with` keyword Uses

1. In Python, the `with` keyword is used to create a context in which a block of code is executed.
2. This is typically used when working with objects that have a __enter__ and __exit__ method


## Python `with` keyword Syntax

```Python
with expression [as variable]:
    with-block
```

## Python `with()` keyword Examples:

let's go through some of examples to understand `with()` keyword in Python

### Example 1: 
Read a file using `with` keyword

```Python
with open("demo.txt","w") as fw:
    fw.write("example for with keyword")

with open("demo.txt","r") as fr:
    print(fr.read())
```

output:

```Python
example for with keyword
```
In this example after writing the program also we can not use close the file here.

### Example 2: 
Read a file and print its contents 

```Python
# Open a file for reading
with open("file.txt", "r") as f:
  # Read the contents of the file
  contents = f.read()

  # Print the contents of the file
  print(contents)
```

output:
```Python
print("Pythonshiksha- best Python tutorial")
```
To get output like this, first create a file named "file.txt" and then when we read that file, it can open and print what it contains, as shown in this example. 

file.txt  
```Python
print("Pythonshiksha- best Python tutorial")
```

The `with` keyword creates the context by calling the __enter__ method on the object, and when the code block finishes executing, it automatically calls the __exit__ method on the object to clean up any resources that were being used. 

The `with` keyword is often used when working with files, but it can be used with any object that has a __enter__ and __exit__ method.

## Summary
In this tutorial we learnt about Python `with` keyword usage with the help of simple examples.