---
title: " Generate random integers between 0 and 9 "
description: "Generate random integers between 0 and 9."
date: "2021-08-06T04:15:05+09:00"
draft: false
link: " Generate random integers between 0 and 9 "
author: "acreddy"
---


We'll learn how to create random integers between 0 and 9 in Python in this tutorial. We'll make use of certain Python built-in functions as well as some custom code. Let's have a look at several different methods for generating random numbers. Python has a number of functions for generating random integers in certain ranges. We'll go over how to use Python's built-in random module to generate random integers. Randint() and randrange() are two important functions in the random module for generating random integers (). We'll also look at how the random module handles float values. To produce random values, an additional module called secrets can also be utilised. 

## Method 1 - Randint() function

This function, which is part of the random module, generates random integers ranging from 0 to 9. This function generates a random integer from a set of values. However, we cannot use a float number in randint(). Python will throw an ValueError .

## Example 1 – Generating a single number

```

# without a loop
import random
print(" A random integer in range 0 to 9 :- " ,random.randint(0,9))

```

## Output

```

Random integer from 0 to 9 :-  3

```

## Example 2 – generating more than one number

```

#with a loop
import random
print('5 random numbers between 0 and 9')
for i in range(5):
	print(random.randint(0,9))

```

## Output

```

5 random numbers between 0 and 9
9
2
3
7
4

```

## Method 2- Randrange() Function 

The randrange() function has three inputs: start, stop, and step. This function generates a random integer from a set of values. The range's upper limit isn't included. Even this function will throw out a Value Error when a floating value input is specified . 

## Example 1

```
import random

print("Random numbers from 0 to 9 - ")
for i in range(10):
    print(random.randrange(10))
```

## Output

```
Random numbers from 0 to 9 - 
2
3
7
8
8
4
4
5
8
8

```

As we can see from the above example, the function generates duplicate values as well to fulfil the range. 

## Example 2 

Here we will be generating numbers in a given range (inclusive)

```
import random

print("Random numbers from 10 to 20 :- ")
for i in range(10):
    print(random.randrange(10, 20)) #This can be any specific range

```
## Output

```
Random numbers from 10 to 20 - 
14
10
18
12
19
11
13
13
10
11

```

## Method 3 – secrets function

To generate random numbers, we can use the secrets module's randbelow() function. It creates random numbers that are cryptographically secure. Python 3.6 introduces the secrets module. For cryptography or security purposes, this is preferable than the random module.

## Example

```
from secrets import randbelow

print("Random integers from 0 to 9 :-")
for i in range(9):
    print(randbelow(9))

```

## Output

```
Random integers from 0 to 9 -
0
1
8
1
5
7
3
2
8

```

## Conclusion

Although we have other methods which we can use to generate random integers , the above described methods are some of the fastest and convenient ways to perform this task.
