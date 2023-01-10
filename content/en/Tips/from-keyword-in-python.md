---
title: "Python 'from' keyword usage, examples"
description: "The 'from' keyword is one of the keyword out of thirty-five keywords in Python"
date: "2022-09-20T12:10:05+09:00"
draft: false
link: "'from' keyword"
author: "harika"
---

## Python `from` keyword

1. The `from` keyword is one of the keyword out of thirty-five keywords in Python.
2. In Python, there are many different modules that may be imported. The `from` keyword can be used to choose a specific method from any module and then utilize it. 

## Python `from` keyword Uses

The `from` keyword is used to import only a specified section from a module.

## `from` keyword syntax in Python

```Python
from <module> import <thing>
```

## Python `from` keyword Examples:

let's go through some of examples to understand `from` keyword in Python

### Example 1:
In Python datetime is a module in that we can select only hour from the datetime module in this case `from` key word is used like this.

```Python
from datetime import time

x = time(hour=18)

print(x)
```
output:

```Python
18:00:00
```

### Example 2: To know system version 

```Python
from sys import version

print(version)
```
output:

```Python
3.8.8 (default, Apr 13 2021, 15:08:07) [MSC v.1916 32 bit (Intel)]
```

## Summary
In this tutorial we learnt about Python `from` keyword usage with the help of simple examples.

