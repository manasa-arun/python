---
title: "How to search for a string in text files in python"
description: "we'll examine the various approaches to finding `a string in a text file`,with simple examples.
"
date: "2023-02-02T03:40:05+09:00"
draft: false
link: "Search string in a text files in python"
author: "harika"
---

## How to search for a string in text files in python

In this article, we'll examine the various approaches to finding `a string in a text file`,with simple example.

When we want to search for a string, number, or anything else, we must first open that file in Python. 

We'll show you how to open and read text files in python.
When these files are opened, we can search for specific strings. 

Text files can contain a wide range of data.
It's not uncommon for these files to need to be searched for strings.
Many functions and modules in the Python standard library make it easier to search for strings in text files. 

1. find and read  method
2. readline/readlines method
3. enumerate method
4. mmap 

1. `find()` and `read()` method to search for a string in text files:
     
    If a file is small, read it into a string and use the `find()` method to see if it contains a string or word. 

    Use the `find()` method of a str class to check the given string or word present in the result returned by the `read()` method.
    
    The `find()` method will return -1 if the given text is not present in a file Print line and line number.


2. `readline/redlines` method to search for a string in text files:
     
    If you want to print line and line number information, use the `readlines()` method instead of the `read()` method. 
    using for loop and `readlines()` method to iterate each line from a file.



3. `enumerate` method to search for a string in text files:
    
    The `enumerate` method is the Efficient way to search `string in a large text file`.
    
    The `enumerate()` function adds a counter to an iterable and returns it in enumerate object. Pass the file pointer returned by the open() function to the enumerate().


### Example 1: search for a string in text file 
```python
def search_str(file_path, word):
    with open(file_path, 'r') as file:
        # read all content of a file
        content = file.read()
        # check if string present in a file
        if word in content:
            print('string exist in a grocery')
        else:
            print('string does not exist in grocery')

search_str(r'D:\new\grocery.txt', 'sugar')
```
output:
```python
string exist in a grocery
```
To get this output first we need to create a txt file,for this i created a `grocery.txt` file like this

```python
sugar 1kg 100
tea powder 1kg 400
cereals 1kg 200
oil  2 300
```
If I search for the word 'sugar' in the above example, it will search in the 'grocery.txt' file and return the results as`string exist in a grocery`.

now let's try another word which is not there in grocery list then it will give output as `string does not exist in grocery`.


### Example 2: search for a string using enumerate
```python
with open(r"D:\new\grocery.txt", 'r') as fp:
    for l_no, line in enumerate(fp):
        # search string
        if 'sugar' in line:
            print('string found in a file')
            print('Line Number:', l_no)
            print('Line:', line)
            # don't look for next lines
            break
```

output:
```python
string found in a file
Line Number: 0
Line: sugar 1kg 100
```

let's try for another word which is not there in grocery text file is 'laptop'
the result is

```python
with open(r"D:\new\grocery.txt", 'r') as fp:
    for l_no, line in enumerate(fp):
        # search string
        if 'laptop' in line:
            print('string found in a file')
            print('Line Number:', l_no)
            print('Line:', line)
            # don't look for next lines
            break
```

output:
```python
nothing will display here
```
so laptop is word not there in grocery text file.

### `mmap` method  to `search for a string in text file`

    `mmap` method is the  fastest and most memory-efficient way to search a string in a large text file.

```python
import mmap

with open(r'D:\new\grocery.txt', 'rb', 0) as file:
    s = mmap.mmap(file.fileno(), 0, access=mmap.ACCESS_READ)
    if s.find(b'oil') != -1:
        print('string exist in a file')
```
output:
```python
string exist in a file
```







