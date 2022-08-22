---
title: "format built-in function in python"
description: " format() built in functions in python"
date: "2022-08-22T10:00:05+09:00"
draft: false
link: "format() Built-in functions"
author: "harika"
---

## format() function in python:
The `format()` function is a one of the built-in functions in python.
`format()` is used for `Formats a specified value`.

The string's placeholder is filled with the formatted value(s) inserted by the format() method. 
The placeholder is defined using curly brackets: {}.


# Syntax:
```
string.format(value1, value2...) 
```
where,
value1, value2... 	Required. One or more values that should be formatted and inserted in the string.

The values can be of any data type.

# Example:
```
print("{} is my country".format("India"))
```
# output:
```
India is my country
```
# Example:
```
# integer 
print(format(5648, "*>+7,d"))

# float number
print(format(690.4567, "^-09.3f"))
```
# output:
```
*+5,648
0690.4570
```

# Formatting Types:

Inside the placeholders you can add a formatting type to format the result:

:< 	
Left aligns the result (within the available space)

:> 	
Right aligns the result (within the available space)

:^ 	
Center aligns the result (within the available space)

:= 	
Places the sign to the left most position

:+ 	
Use a plus sign to indicate if the result is positive or negative

:- 	
Use a minus sign for negative values only

:g 		
General format

:G 		
General format (using a upper case E for scientific notations)

:o 	
Octal format

:x 	
Hex format, lower case

:X 	
Hex format, upper case

:n 		
Number format

:% 	
Percentage format

:  	
Use a space to insert an extra space before positive numbers (and a minus sign before negative numbers)

:, 	
Use a comma as a thousand separator

:_ 	
Use a underscore as a thousand separator

:b 	
Binary format

:c 		
Converts the value into the corresponding unicode character

:d 	
Decimal format

:e 	
Scientific format, with a lower case e

:E 	
Scientific format, with an upper case E

:f 	
Fix point number format

:F 	
Fix point number format, in uppercase format (show inf and nan as INF and NAN)


