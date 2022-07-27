---
title: "bytearray built-in function in python"
description: "bytearray built in functions in python"
date: "2022-07-26T11:00:40+09:00"
draft: false
link: "bytearray() Built-in functions"
author: "harika"
---

## iter() in python:
The `iter()` function is one of the built-in function in python.
`bytearray()` is used for `Returns an array of bytes`.

# syntax:
```
bytearray([source[, encoding[, errors]]])
```
bytearray() method returns a bytearray object (i.e. array of bytes) which is mutable (can be modified) sequence of integers in the range 0 <= x < 256.

# bytearray() Parameters:

bytearray() takes three optional parameters:

    source (Optional) - source to initialize the array of bytes.
    encoding (Optional) - if the source is a string, the encoding of the string.
    errors (Optional) - if the source is a string, the action to take when the encoding conversion fails (Read more: String encoding)

The source parameter can be used to initialize the bytearray in the following ways:

String
	Converts the string to bytes using str.encode() Must also provide encoding and optionally errors
Integer
	Creates an array of provided size, all initialized to null
Object
	A read-only buffer of the object will be used to initialize the byte array
Iterable
	Creates an array of size equal to the iterable count and initialized to the iterable elements Must be iterable of integers between 0 <= x < 256
No source (arguments)
	Creates an array of size 0.
bytearray() Return Value

The bytearray() method returns an array of bytes of the given size and initialization values.

# Example 1:
```
str = "pythonshiksha"
array = bytearray(str, 'utf-16')
print(array)
```
output:
```
bytearray(b'\xff\xfep\x00y\x00t\x00h\x00o\x00n\x00s\x00h\x00i\x00k\x00s\x00h\x00a\x00')
```

# Example 2: To find length of array
```
my_list = [29,31,11,4,24]
  
array = bytearray(my_list)
  
print(array)
print("Count of bytes:", len(array))
```
output:
```
Count of bytes: 5
```
Note:
If you want the immutable version, use the bytes() method.