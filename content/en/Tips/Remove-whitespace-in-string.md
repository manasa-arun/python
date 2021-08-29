---
title: " Remove all whitespace in a string "
description: "Remove all whitespace in a string."
date: "2021-08-06T04:15:05+09:00"
draft: false
link: " Remove all whitespace in a string "
author: "acreddy"
---

## Introduction

In Python, a string can contain large amounts of whitespace. You may need to delete all of these white spaces in Python at some point during your programming. We can't change the value of a Python String because it's immutable. Any function that manipulates a string value returns a new string, which must be explicitly assigned to the string; otherwise, the string value will remain unchanged. 

In Python, there are several methods for removing spaces from a string. This article aims to give a quick overview of the many functions available for removing whitespace from a string. 

Let us consider the following quote from Dalai Lama,  as the input from which we need to remove spaces –  “Do not let the behaviour of others destroy your inner peace”

## Method 1 – strip() method

This function will eliminate all trailing and leading whitespaces.

## Example

```
test_string ="\n \n \t Do not let the \t \n behaviour of others destroy your 	inner peace \t\t\t\t\n		."
print(test_string.strip())

```
## Output

```
Do not let the 	 
 behaviour of others destroy your 	inner peace 				
.

```

Here we can observe that the trailing and the leading whitespaces are only removed. The others remain intact. In case we are required to remove ONLY the leading or ONLY the trailing whitespaces, we can make use of  the lstrip() and the rstrip() methods. These remove the leading and the trailing white spaces respectively. 

## Method 2 – replace() function

We can make use of the replace function to replace any whitespace characters in the given string. This function accepts the following parameters – 
1.	The string to be replace
2.	the string to be substituted 

## Example 

```
test_string ="Do not let the \t \n behaviour of others destroy your      inner peace."
print(test_string.replace(" ",""))
```

## Output

```
Donotletthe	
behaviourofothersdestroyyourinnerpeace.

```

## Method 3 – using join() with split()

You can use the join() function in conjunction with the string split() function to trim all duplicate whitespaces and newline characters.

## Example 

```
s = "Do not let the \t \n behaviour of others destroy your      inner peace \t."
s1= "".join(s.split())
print(s1)

```

## Output 

```
Donotletthebehaviourofothersdestroyyourinnerpeace.

```
## Method 4 – Using Regular Expression function

We may also match whitespace with a regular expression and replace it with the re.sub() function. A regular expression, often known as RegEx, is a set of characters that together constitute a search pattern. RegEx is a pattern replacement tool that searches for and replaces certain patterns. Regular expressions are supported by a built-in module in Python called re.
Importing the module is as follows:

```
import re

```

There are different ways in which we can use RegEx to remove whitespaces- 
1.	\s  -> this matches all the whitespaces and removes them
2.	^   -> removes all the leading whitespace
3.	$   -> matches all trailing whitespaces
4.	|   -> used to match either of the above conditions



## Example 4.1

```
>>> s='      \t Welcome to the world \t \t        '
>>> re.sub(r"\s+","",s)
'Welcometotheworld'

```
## Example 4.2

```
>>> s='      /t Welcome to the world /t /t        '
>>> import re
>>> re.sub(r"^\s+","",s)
'/t Welcome to the world /t /t        '

```

## Example 4.3 

```
>>> s='      /t Welcome to the world /t /t        '
>>> import re
>>> re.sub(r"\s+$","",s)
'      /t Welcome to the world /t /t'

```

## Example 4.4

```
>>> s='      \t Welcome to the world \t \t        '
>>> re.sub(r"^\s+|\s+$", "", s)
'Welcome to the world' 

```

## Conclusion

Here we have seen some of the ways in which we can remove the whitespaces in a string.

