---

title: "How do I concatenate items in a list to a single string"
description: "  Three techniques for concatenate items in a list to a single string"
date: "2022-04-20 T010:32:05+09:00"
draft: false
link: "strings"
author: "harika"
---

## introduction:
Strings in python are defined as aet of characters represented in the quotation marks.

** example:
`str1='harika'`
`str2="harika"`
like this we can represent strings in single and double quotes.

## concatenate items in a list to a single string:
## using '+'operator:
A common operation that performed on strings in `concatenation`.
 or
appending one string to the end of another string.

```
first_name="vamshi"
last_name="krishna"
fullname=first_name+last_name
print(fullname)
```
output:
```
vamshikrishna
```

in this output we got a concatenated result but in this no space is there in between two names.

Example:

```
first_name="vamshi"
last_name="krishna"
fullname=first_name+" "+ last_name
print(fullname)
```
output:
```
vamshi krishna
```
now we got a output with spaces in between two names for this we can use 
" "+ is used in 3rd line of python program.
check program and try with another names.

note:
The concatenation can be done with two strings`(string+string)`.
The concatenation can not be done with`(string+int)`.


## using join():

The join() method takes all items in an iterable and joins them in to single string

syntax:
```
'separator'.join([ 'List','of',' string' ])
```

example:
```
>>> names_list = ['harika', 'saanvi', 'santhosh']
>>> print("".join(names_list))
harikasaanvisanthosh

>>> print(" ".join(names_list))
harika saanvi santhosh

>>> print("-".join(names_list))
harika-saanvi-santhosh
```
like this we can easily use join() to  concatenate items in single string in python.

## using (*)Repetition operator:
A Repetition operatorcreates a string that contains n repeted copies of string.
Example:
`my_string ='W'*5`
we can get this output `WWWWW` W is printed in 5 times.

another Example is:

print('heloo' *3)
this code will get like this `heloohelooheloo` heloo word printed 3 times.

```
str1="python"
print ("String 1:",str1)
str1=str1*3
print("Concatenated same string:",str1)
```
output:
```
String 1: python
Concatenated same string:  pythonpythonpython
```
like this string repetition method is very easy to use with this 
`* `operator.

Note: Before concatenating a non-string variable with a string, you must first turn the non-string variable into a string. 

The repetition can not be done with two strings(string+string).
The repetition can be done with (string+int).
## 



