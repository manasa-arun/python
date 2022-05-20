---

title: "how to remove specific substring from a set of strings in python"
description: " Best and easy methods how to remove specific substring from a set of strings in python"
date: "2022-05-20 T010:07:05+09:00"
draft: false
link: "JSON"
author: "harika"
---

## introduction:

**Strings** are an array of Unicode characters occupying a storage of few bytes. 

If you come from a different language, there are high chances of your interaction with the `char` keyword, but in python there is no such `char` keyword and thus we can say that a single letter inside quotation marks in python is a string with length 1.

Strings behave the same way as like arrays and thus can be accessed by using the `[]` operator.

A substring is a sequence of Unicode characters within a string.

Examples of Strings in python:
```
‘python’ , ‘coding’ , ‘abc’ , ‘d’ , ‘’ , 'Python is a good language'
```

## using str.replace():

Here is the solution to removing a sub string from a set of strings.

We can delete the last set of substrings from the main string using this way. 

using str.replace("new", "") method can delete only last string from main set of strings. 

**Example:**

```
my_string = "programming"

new_string = my_string.replace("ming", "")

print(new_string)
```
output:
```
progrm
```
here we can observe last letters can removed here, `ming` is removed and displyed `progrm` from main string `programming`.

## using string.replace():

strings are immutable in python, we can not remove  astring here just replaced a new string like this

**Example:**
```
my_text = "python can learn easily!"
x = my_text.replace("learn", "study", 1)
x = my_text.replace("easily", "quickly", 2)
print(x)
```
output:
```
python can study quickly
```   
here 'learn' replaced with 'study'
and 'easily' can replaced with 'quickly'

try this simple python programing code and replace with a new strings

## using for loop +replace():

using two methods `for loop+replace` functions can solve this problem easily 

**Example:**

```
my_str = "python can learn easily"
  
print("The original string is : " + my_str)
  
sub_list = ["learn"]
  
# Using loop + replace() 
for sub in sub_list:
    my_str = my_str.replace(' ' + sub + ' ', ' ')

print("The string after substring removal : " + my_str) 
```
output:
```
The original string is : python can learn easily
The string after substring removal : python can easily
```
`can` substring  is removed from original string here.

## conclusion:

In this article `remove specific substring from a set of strings in python'  and 'replace old string ith ne string` concept also explained easily with simple examples to evaryone can understand easily.

