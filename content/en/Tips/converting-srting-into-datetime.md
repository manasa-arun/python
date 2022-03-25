---
title: "converting string into datetime"
description: "Learn how to convert string to datetime"
date: "2022-03-24T02:11:05"
draft: false
link: "Add keys to Dictionary"
author: "harika"
image: "images/featured/addNewKeysPythonDictionary.png"

---
## converting string into datetime:

## introduction:

Handling dates and times is one of the many typical difficulties we confront in software development. 

For example, after receiving a date-time string from an API, we must convert it to a human-readable format.

 Again, the conversion will be different if the same API is used in different timezones. 
 
 A good date-time library will transform the time according to the timezone. This is just one of many factors to consider when dealing with dates and times.

 
 Thankfully, Python comes with the built-in module `datetime` for dealing with `dates and time`,Using this module, we can easily parse any date-time string and convert it to a datetime object.

## how to convert string to datetime:

The `datetime` module consists of three different object types: `date`, `time`,` and `datetime`. 

`dateobj = date(year, month, day)`
`timeobj = time(hour, minute, second)`
`datetimeobj = datetime(year, month, day, hour, minute, second)`

Obviously the `date` object holds the `date`, `time` holds the `time`, and `datetime` holds both `date and time`.

## how to use datetime module:

we should be able to parse date/time string representations and obtain arguments for the constructors listed above.

`For example`
the default string representation of the date is 'YYYY-MM-DD', whereas the time is 'HH:MM:SS', and the datetime is 'YYYY-MM-DD HH:MM:SS'.

`datetimeobj = datetime(year, month, day, hour, minute, second)`

The string representation of date and time, on the other hand, may vary depending on the user's preferences. 

For instance, one may use the DD-MM-YY format or show the month by name, such as 16-Oct-2020.

This is where the datetime class's strptime() method comes in handy.

`datetime.datetime.strptime(string, format)`

```
#datetime.strptime()

from datetime import datetime
datetime_str = 'may 29 2017 07:30AM'
datetime_obj=datetime.strptime(datetime_str, '%b %d %y %I:%M&P')
print(datetime_obj)
```
output:
```
2017-05-29 07:30:00
```

In this datetime we have to fallow some rules to get exact format of time and date, which we used in python program.

*`%b` is used for to indicate `month as local' abbreviated name
example:
`jan,feb..dec` we can use any month name here

*`%B` for Month as locale’s full name.
`january,february..december`

*`%m` used for Month as a zero-padded decimal number.`01, 02, …, 12`

*`%y` used for Year without century as a zero-padded decimal number.	
`01,02,03...99`

*`%Y` used for Year with century as a decimal number.`0001, 0002, …, 2013, 2014, …, 9998, 9999`

*`%H` used for Hour (24-hour clock) as a zero-padded decimal number.
`00, 01, …, 23`

*`%I` used for Hour (12-hour clock) as a zero-padded decimal number.`01, 02, …, 12`

*`%M` used for Minute as a zero-padded decimal number.
`00, 01, …, 59`

*`%S` used for Second as a zero-padded decimal number.`00, 01, …, 59`

*`%p` used for Locale’s equivalent of either AM or PM.`AM, PM (en_US)`

instead of using `jan we can use %b` like this in python 3 this format codes are used to get exact format of datetime.

*`%a` used for Weekday as locale’s abbreviated name.`Sun, Mon, …, Sat (en_US)`

*`%A` used for Weekday as locale’s full name.	
`Sunday, Monday, …, Saturday (en_US)`

*`%w` used for Weekday as a decimal number, where 0 is Sunday and 6 is Saturday.`0, 1, …, 6`

*`%d` used for Day of the month as a zero-padded decimal number.`01, 02, …, 31`

*`%f` used for Microsecond as a decimal number, zero-padded to 6 digits.`000000, 000001, …, 999999`

*`%z` used for UTC offset in the form ±HHMM[SS[.ffffff]] (empty string if the object is naive).`(empty), +0000, -0400, +1030, +063415, -030712.345216`

*`%Z` used for Time zone name (empty string if the object is naive).
`(empty), UTC, GMT`

*`%j` used for Day of the year as a zero-padded decimal number.
`001, 002, …, 366`

*`%U` Week number of the year (Sunday as the first day of the week) as a zero-padded decimal number. All days in a new year preceding the first Sunday are considered to be in week 0.`00, 01, …, 53`

*`%W` used for Week number of the year (Monday as the first day of the week) as a zero-padded decimal number. All days in a new year preceding the first Monday are considered to be in week 0.`00, 01, …, 53`

*`%c` used for Locale’s appropriate date and time representation.`Tue Aug 16 21:3`

*`%x` used for Locale’s appropriate date representation.`08/16/88 (None)`
	
*`%X` used for Locale’s appropriate time representation.
`21:30:00 (en_US)`,
`21:30:00 (de_DE)`

like this every module have its own speciality to get user preferenced format.


	




