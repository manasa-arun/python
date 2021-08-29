---
title: " A string to Lowercase "
description: "A string to Lowercase."
date: "2021-08-06T04:15:05+09:00"
draft: false
link: " A string to Lowercase "
author: "acreddy"
---


## Introduction

You might want to transform the contents of a string to lowercase while working with it in Python.
You might be designing a sign-up form that transforms a user's email address to lowercase.
Because strings are case-sensitive, this is a common procedure to ensure that another account cannot be established using the same email in uppercase.

## The .lower() function

The function .lower() is a built-in Python function used to work with strings.
The.lower() method takes no arguments and converts each capital letter to lowercase to return lowercased strings from the given string. It returns the original string if the input string contains no uppercase characters.
They syntax for this function is as follows –

```
String_to_convert.lower()

```

. lower() is a string function in Python. It is applicable to all cased characters in a string.

## Example 

```

T_str="This is An Example Of UPPER CASE Sentence"
print(T_str.lower())

```

## Output

```

this is an example of upper case sentence

```

Because symbols and numbers are not case-sensitive, lower() will return them in their original condition. In a string, just the Unicode characters are transformed to lowercase. To avoid the case wherein the string is already in lower case, we can make use of certain in-built functions such as islower() to check if there are any characters that require to be converted into lower case.

It might be the case wherein we are checking to avoid and remove any duplicates which are just reiterated data with changes in case. To perform such a task , a combination of lower() and islower() functions can be utilised. 

## Example 

```
# Email is valid if it contains only lower case characters.

email="abcde@bptfp.net"

if email.islower():
	print("The Email id is a valid one")
else:
	print("Email id is not valid")

email_1="AbcdE@bptfp.net"

if email_1.islower():
	print("The Email id is a valid one")
else:
	print("Email id is not valid")

# Combination of both .

if email.islower() and email_1.lower():
	print(" Both email's differ in Case")

```
## Output

```
The Email id is a valid one
Email id is not valid
 Both email's differ in Case
[Finished in 75ms]

```

## Conclusion

The lower() function in Python can be used to convert a string to lowercase and return a new string. To see if a string contains an uppercase character, use the Python isLower() method. We looked at the two primary lowercase Python methods in this tutorial: lower() and isLower (). We looked at a few examples of these strategies in operation as well.


 