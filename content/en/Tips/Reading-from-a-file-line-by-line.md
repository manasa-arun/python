---
title: " Reading from a file into a list "
description: "How to read contents of a file into a list."
date: "2021-08-01T04:15:05+09:00"
draft: false
link: "Reading from a file into a list"
author: "acreddy"
---

## Introduction

By storing data in files, you can keep track of the data that a software is working with.
When dealing with a code, this means you won't have to produce data repeatedly.
You simply read the information from a file. Here we will discuss the possible ways in which we can achieve this. 
Here we assume that we are using a text file – test.txt,  with the contents- 

```
This is Line 1 
This is Line 2
This is Line 3
This is Line 4 

```
## Method 1 -Using readlines() and strip() 

The readlines() function in Python reads till the end of the file and produces a list containing the lines. The syntax is as follows –

```
File_Object.readlines(byte_size)

```
Instead of reading up to EOF, if the optional argument is specified, full lines totaling approximately the mentioned byte sizes are read. 
When an EOF is detected, an empty string returned.

The strip() method is used to remove any whitespaces that might be encountered in the lines. This removes the newline character ‘\n’ and the tab space character ‘\t’ .Let us now look at an example as to how these functions are to be used to read lines into a list.

**Example 1**

```
with open('test.txt') as f:
    Contents = f.readlines()
# we may also want to remove whitespaces like `\n` at the end of each line
li = [x.strip() for x in Contents]
print(li)

```

**Output**

```
['This is Line 1', 'This is Line 2', 'This is Line 3', 'This is Line 4']

```

## Method 2- With line.rstrip() function

The rstrip() function is used to remove the characters from the right based on the argument passed to it. The syntax is as follows –
```
String_name.rstrip(parameter)
```
The parameter for rstrip() is optional. If it is not mentioned , then all whitespaces to the right will be removed. 
The rstrip() method returns a value that contains a copy of the string with the trailing characters removed.
Thus  ,we can utilize the rstrip() method to serprate element out of each line and store them in a list.

**Example 2**
```
with open('/Users/acreddy/Downloads/Python/test.txt') as f:
    lines = [line.rstrip() for line in f]
print(lines)

```
**Output**
```
['This is Line 1', 'This is Line 2', 'This is Line 3', 'This is Line 4'] 
```

## Method 3 – With loops and strip() function

Another approach is to use a for loop to iterate over the lines in the file one by one and then append them to a list using the append() function.
The strip() function again comes into play which allows us to strip the newline character.

**Example 3**
```
with open('/Users/acreddy/Downloads/Python/test.txt') as f:
    lines = []
    for line in f:
        lines.append(line.strip('\n'))
    print(lines)
```

**Output**
```
['This is Line 1', 'This is Line 2', 'This is Line 3', 'This is Line 4']

```

## Method 4- With splitlines()

Splitlines() splits a string at line breaks and produces a list of lines. It splits the string at line breaks and returns a list of split strings. The syntax is as follows –

```
Str.splitlines([keepends])

```
The parameter *keepends* is optional. It is a Boolean value i.e, it can be True or False. By default the value is False. A new line (\n), carriage return (\r) are examples of line breakers. 
The function splitlines() returns lines separated by a comma.

**Example 4**

```
with open('/Users/acreddy/Downloads/Python/test.txt', 'r') as infile:
    data = infile.read()  # Read the contents of the file into memory.
# Returns a list of the lines, breaking at the line boundaries.
li = data.splitlines()
print(li)

```

**Output**

```
['This is Line 1', 'This is Line 2', 'This is Line 3', 'This is Line 4']
[Finished in 154ms]

```


## Conclusion

We have seen different ways in which we can read lines from a file and into a list.
