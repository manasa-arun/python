---

title: " python typeError: a bytes-like object is required,not'str'when writing to a file in python3 "
description: " range function can solve  "
date: "2022-05-10 T009:35:05+09:00"
draft: false
link: "range function to solve typerror in python"
author: "harika"
---
## introduction:

Strings are a collection of characters, whereas the latter is a sequence of bytes, also called Unicode objects. 

In Python3, all strings are Unicode objects by default.

In Python 2, we can convert strings to Unicode and vice-versa using the encode and decode functions.

## how to fix "bytes-like objects is required not str":

While developing in Python, programmers frequently encounter this type of error.
When data types are mismatched, the typeError occurs.

When you run the same code on multiple Python versions, this happens.
When coding in Python 2, 

for example, you will have no difficulty processing bytes and Unicode characters.
However, when running the same code in Python 3, issues may develop. 

look at this Example:



