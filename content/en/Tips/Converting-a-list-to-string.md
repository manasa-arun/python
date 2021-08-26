---
title: " Convert a list to string "
description: "Convert a list to string."
date: "2021-08-06T04:15:05+09:00"
draft: false
link: " Convert a list to string "
author: "acreddy"
---


When a list is given and we convert it to a string, we may encounter a variety of situations.
For example, converting a list of strings or an integer list to a string. 

## Example

```
Input ->  [‘Hear’ , ‘the’, ‘unheard’]
Output -> Hear the unheard

Input -> [‘I’ , ‘want’ , ‘ to’ , ‘buy’ , 1000 , ‘nachos’ , ‘packets’]
Output -> I want to buy 1000 nachos packets

```

There are various methods in which we can perform the above.

## Method 1 – The naïve method

Iterate through the list, adding an entry for each index in a new string.

## Example

```
s=['Welcome' , 'to', 'Python' , 'Shiksha']
str1 =""

for i in s:
	str1+=i

print('The list -> ' , s)
print('Combined String : ' ,str1)

```

## Output

```
The list ->  ['Welcome', 'to', 'Python', 'Shiksha']
Combined String :  WelcometoPythonShiksha

```

## Method 2 – join() function

The join() function combines all of the elements in an iterable into a single string. The separator must be supplied as a string. The syntax is as follows –

```
String.join(iterable)

```

This accepts one parameter- iterable . Any iterable object with just strings as returned values
We can perform the same operation by utilizing the join() function.

## Example 

```
s=['Welcome' , 'to', 'Python' , 'Shiksha']
str1 =""

a=str1.join(s)

print('The list -> ' , s)
print('Combined String : ' ,a)

```

## Output

```
The list ->  ['Welcome', 'to', 'Python', 'Shiksha']
Combined String :  WelcometoPythonShiksha
[Finished in 68ms]

```

However, what if the list's elements are both strings and integers? The above code will not function in certain situations. While adding to string, we must convert those integers to a string. The next method achieves this.

## Method 4 – List Comprehension

When you wish to construct a new list based on the values of an existing list, list comprehension provides a more concise syntax. The syntax is as follows –

```
New_list= [ <condition> for i in iteration if condition == True]

```

We can also use list comprehension to convert a list to a string, as we can see in the below example.

## Example 

```
s=['Welcome' , 'to', 'Python' , 'Shiksha']

a = ' '.join([str(e) for e in s])

print('The list -> ' , s)
print('Combined String : ' ,a)

```

## Output
```
The list ->  ['Welcome', 'to', 'Python', 'Shiksha']
Combined String :  Welcome to Python Shiksha
```
As we can observe from the above example. When we use the join function, we add the space , thus the output has some space between the words.

## Method 5 – map() function

After applying the specified function to each item in a specified iterable, the map() method produces a map object (which is an iterator) of the results (list, tuple etc.) 
They syntax is as follows –

```
Map(function, iteration)

```

Where – 
•	function : It's a function that maps each element of an iterable to..
•	Iteration : It's an iterable that will be mapped.

To map string_test (for converting elements in a list to strings) to a specified iterator, the list, use the map() function. 

## Example

```
s=['Welcome' , 'to', 'Python' , 'Shiksha']

a = ' '.join(map(str,s))

print('The list -> ' , s)
print('Combined String : ' ,a)

```

## Output

```

The list ->  ['Welcome', 'to', 'Python', 'Shiksha']
Combined String :  Welcome to Python Shiksha

```

## Conclusion

We have explored different ways in which we can convert a list into a string.
