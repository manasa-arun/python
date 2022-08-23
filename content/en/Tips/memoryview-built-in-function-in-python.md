---
title: "memoryview built-in function in python"
description: " memoryview() built in functions in python"
date: "2022-08-23T01:30:05+09:00"
draft: false
link: "memoryview()Built-in functions"
author: "harika"
---

## memoryview() function in python:
The `memoryview()` function is a one of the built-in functions in python.
`memoryview()` is used for `Returns a memory view object`.

The memoryview() function returns a memory view object from a specified object.

# memoryview:
A memory view is a safe way to expose the buffer protocol in Python.

It allows you to access the internal buffers of an object by creating a memory view object.

# buffer protocol:
We can utilise the buffer protocol to grant another object access to the huge data without copying it.

This reduces memory usage and enhances programme execution speed. 

This protocol is only accessible to us at the C-API level and not using our normal codebase.

So, in order to expose the same protocol to the normal Python codebase, memory views are present.


# Syntax:
```
memoryview(obj)
```
where,
obj is A Bytes object or a Bytearray object.

# Example:
```
x = memoryview(b"pythonshiksha")

print(x)

#return the Unicode of the fifth character
print(x[5])

#return the Unicode of the third character
print(x[3])
```
# output:
```
<memory at 0x1468b5fbfa00>
110
104
```

