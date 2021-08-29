---
title: "Check if string is empty"
description: "How to Check if string is empty."
date: "2021-07-30T04:18:05+09:00"
draft: false
link: "Check if string is empty"
author: "acreddy"
---


## Introduction

Python strings are immutable, which means we could alter them based on the operations we do. Python's most essential functionality is string manipulation. Many methods, such as string slicing techniques, looping through the components, and string methods, can be used to modify the string. But sometimes we need to verify if the Python string is empty or not when the list is empty. Here we'll look at how to verify if a string is empty or not.
There are different ways in which we can check for an empty string –
1.	Len() method
2.	Not operator
3.	Strip()
4.	Using len() and strip() 
5.	Using ‘not’ and isspace()


## Method 1 -> len() function

We'll use python's len() function to determine the length of the string.
Then, if the length of the string equals 0, the string is empty; otherwise, it is not.

## Example 1

```

#provide an input empty with and without spaces 
string1 = ""
string2 = "    "
 
x = len(string1)
y = len(string2)
 
if x == 0:
    print("The string is empty")
else:
    print("The string is not empty")

if y == 0:
    print("The string is empty")
else:
    print(" The string is not empty")

```

## Output

```

The string is empty
 The string is not empty

```

We've used two input strings, string1 and string2, in this example. String2 has whitespaces, and string1 is an empty string. The length of each string was then determined using Python's len() function. Then we used the if-else loop to check if the string's length is equal to 0, in which case the print string is empty, and in which case the print string is not empty. Whitespaces in the string are not recognized as empty by len(), resulting in a not empty string.
Finally, we printed the result of both strings.

## Method 2 –> Using Not Operator

The not operator performs the same job as the len() function. In Python, an empty string is always equal to False. The not operator can be used to determine if a string is empty or not.

## Example 2

```

string1 = ""
string2 = "    "
 

if not string1:
    print("The string is empty")
else:
    print("The string is not empty")

if not string2:
    print("The string is empty")
else:
    print(" The string is not empty")

```

## Output

```

The string is empty
 The string is not empty

```

We've used two input strings, string1 and string2, in this example. As like the above example , there is one blank string and one non-blank string. Then we used an if else condition to check if the string is empty if it is not in the string. It is not, however, empty. Whitespaces are not treated as empty strings by the not operator, therefore the result will be not an empty string of the second input string. Finally, the result has been printed.

## Method 3 -> using strip() function

Whitespaces in strings are sometimes not regarded as empty strings.
As a result, we can use the strip() method to check for whitespaces as well as the empty string.

## Example 3

```

string1 = ""
string2 = "    "
 
if string1.strip():
    print("string is not empty")
else:
    print("string is empty")
     
if string2.strip():
    print("string is not empty")
else:
    print("string is empty")

```

## Output

```

string is empty
string is empty

```


## Method 4 -> using len() and strip() 

In Python, use the len() + string.strip() method to verify for a pure empty string. The method string.strip() eliminates whitespace from a string. If there is any space in the string, the strip() method removes it, and the len() function checks if the string is empty or not.

## Example 4 

```

string1 = "    Hi There      "
string2 = "      "


if(len(string1.strip())):
    print("The string is not empty")
else:
    print("The string is empty")

if(len(string2.strip())):
    print("The string is not empty")
else:
    print("The string is empty")

```

## Output

```

The string is not empty
The string is empty

```

In the above example, we remove all the spaces and verify the length of the string; if it returns 0, the string is empty; otherwise, it is not. Because the string contains specific letters, you can see that it is not empty in this case. As a result, the length of the string is returned by the len() function, and the if condition returns True.  

## Method 5 -> using ‘not’ and isspace()

The string.isspace() method determines whether the string includes any spaces.
If there is any space in the string, it returns True. Otherwise, False is returned. We utilize a string and not string combination. The isspace() function determines if a string is empty or not, independent of the presence of a space. This technique is more efficient than strip() since it needs doing the strip operation, which takes time to compute if the string has a lot of spaces.

## Example 5

```

string1 = "      "


if(string1 and not string1.isspace()):
    print("The string is not empty")
else:
    print("The string is empty")

```
## Output

```

The string is empty

```



Here , we have used a variable string1, which consists of spaces. The if-else condition has been used. We used the isspace() method in the if-else condition, which checks for all string spaces. Finally, the output has been produced, and you can see that the string is empty.


## Conclusion

In this article, we learnt how to verify whether a string is empty or not, as well as whether it contains just whitespaces. According to the requirements of your program or project, you can utilize any of the ways you choose.












