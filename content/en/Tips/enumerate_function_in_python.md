---
title: "enumerate function in python"
description: "enumerate built in functions in python"
date: "2022-06-28T11:25:05+09:00"
draft: false
link: "enumerate() built-in function"
author: "harika"
---

## enumerate() in python:
`enumerate()` is a one of the built in functions in python.

In python enumerate() function can acts as a counter, it will count the items present in list or tuple.

## Syntax: 

enumerate(iterable, start=0)

## Parameters:

Iterable: any object that supports iteration
Start: the index value from which the counter is to be started, by default it is 0

**Example:**
```
students =['saanvi','kathya','hasya']
print(list(enumerate(students)))
```
**output:**
```
[(0,saanvi),(1,katya),(2,hasya)]
```
Like this the counter starts from 0 and ends when all the list of variables executes
