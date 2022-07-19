---
title: "chr and ord functions in python"
description: "how to use  chr and ord functions in python"
date: "2022-06-28T011:00:05+09:00"
draft: false
link: "chr() ord() built-in functions in python"
author: "harika"
---

## introduction chr() and ord():

chr() and ord() functions both are Built in functions in python.

These functions can used to convert `unicode values to character` and `character to unicode`  like this check examples here. 

## ASCII values:
Every chracter is represented by ASCII value.

This ASCII values is a string encoding format.
ASCII values can represent only 256 values.

Example:
A-65
a-97

## UNICODE:

Every form of character, including letters, symbols, and emojis, has a numerical value according to the Unicode standard.

The standard made it considerably simpler for computers to comprehend symbols, which was especially helpful given how many new symbols are being introduced to the internet. 

UNICODE is superset of ASCII values.

It is represent multiple number of values compare to ASCII.
A-65
a-97
all the values are same in UNICODE and ASCII values.

## ord(): covert char to unicode:
The Python `ord()` function converts `a character into an integer` that represents the Unicode code of the character. 

**Example:**
```
ch =input("Enter character to find corresponding UNICODE value:")
print(ord(ch))
```
**output:**
```
Enter character to find corresponding UNICODE value:D
68
```

NOTE:
IN output if e enter two characters it will give error like this:

**output:**
```
Enter character to find corresponding UNICODE value:AB
Traceback (most recent call last):
  File "c:/Users/Vamshi/date.py", line 2, in <module>
    print(ord(ch))
TypeError: ord() expected a character, but string of length 2 found
```
why because the character length is `one`.
We can pass in any `single string characte`r and the function will return an integer.


## chr(): convert unicode to char

The `chr()` function converts a Unicode code `character into the corresponding string`.

**Example:**
```
unicode =int(input("Enter  UNICODE value to find corresponding value:"))
print(chr(unicode))
```
**output:**
```
Enter  UNICODE value to find corresponding value:100
d

Enter  UNICODE value to find corresponding value:68
D
