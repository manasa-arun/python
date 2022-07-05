---
title: "How can i read inputs as numbers"
description: "Python has a two methods to read inputs as numbers"
date: "2022-04-29T02:26:05+09:00"
draft: false
link: " read input as numbers"
author: "harika"
---

## introduction:

`input` is any data type that the program receives while it is running.
one common form of input is data is typed on the keyboard.
 
## How can i read inputs as numbers:

You may be wondering how developers frequently interact with users.
It is possible, however, with the help of the `input function`.

Most importantly, the primary goal of using the inputs is to obtain or provide data from the users. 

Nowadays, several programs have dialog boxes to ask the users to provide similar or distant inputs. 

In Python 2, there are two different kinds of in-built functions. 

in- built functions help in reading input given by the user using keywords.

## input() in python2.x:

It will collect information from the user at first.
The expression will be evaluated in the next step 

(here, Python automatically identifies the input value as a string or list, or a number).

In other words, if the user's input is erroneous, Python will display a syntax error or an exception.

**Example:**
```
user_num = input("Enter number and hit enter ")
print("Printing type of input value")
print("type of number ", type(user_num))
```
output:
```
Printing type of input value
type of number  <class 'str'>
```
Python 3 has a built-in function input() to accept user input. But it doesn’t evaluate the data received from the input() function,

i.e., The input() function always converts the user input into a string and then returns it to the calling program.

**Example:**

user can know the type of data type which user can entered in program using this python code try and run with your own number.

```
num = int(input('Enter a number: '))
print(type(num))
```
output:
```
Enter a number: 7
<class 'int'>
```
here we can enter 7 number,the number is integer type as we got output,
change the number and try yourself.

## using raw_input():

This function takes what the user types directly from the keyboard.
It converts to a string and then returns the value to the variable, which is what we want to do. 

raw_input does not exist in Python 3. So, the older raw_input() is replaced with the input(), and the older input is replaced. 

input data type can be evaluated by `eval(input()) function`. 

It is a built-in function. The input function is used only in Python 2.x version.

In Python 3.x, the raw input() function is comparable to the input() function.
The raw input method in Python 2.x is recommended for developers.
Because the input function in Python 2.x contains a vulnerability. 

Example:
```
name=raw_input('Enter your name : ')
print ("Hi %s, Let us be friends!" % name);
```
output:
```
Enter your name : saanvi
Hi saanvi Let us be friends!
```
## conclusion:
In this `split()` is used mainly hen we want multiple strings or integers.
input(), raw_input() methods can use this to read inputs as numbers.









## using floating numbers:
we can put floating numbers also instead of integers directly or else we can convert int numbers to float numbers.

example:
```
data = float(input("Enter a Number: "))
print(data)
print(type(data))
```
output:
```
Enter a Number: 6
6.0
```
here we entered int number 6 it converts float number and displayed as 
6.0.


## using split():

we can put multiple string or integer values in one data at atime by using `split()`.

`split()` is used to divide the input value with ‘,’. as shown below example.

Example:
```
int = input("enter multiple names with separator:- ")
int= int.split()
print(int)
```
output:
```
enter multiple names with separator:- 'harika saanvi vamshi'
["'harika", "saanvi'","'vamshi"]

```
here we can enter numbers also that is depends on user.
