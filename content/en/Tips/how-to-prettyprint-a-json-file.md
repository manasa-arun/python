---

title: "How to prettyprint a json file in Python"
description: " Best and easy method to  prettyprint a json file in Python"
date: "2022-05-05T10:09:50+09:00"
draft: false
link: "JSON"
author: "harika"
---

## introduction:

JSON stands for `JavaScript Object Notation`,is a text-based data format that is interchangeable with many programming languages.

Essentially, pretty printing JSON means having proper indentation, `white spaces` and `separators`. 

JSON is commonly used for data transmission between client-server applications. 

## How to prettyprint a json file in Python:

`dumps()` method is used to print prettyprint in JSON.

The json.dumps() method takes the json object and returns a JSON formatted string. 

The indent parameter is used to define the indent level for the formatted str

**Syntax:**

`json.dumps(indent,separator)`

The `indent `argument specifies the number of spaces between key and value, while the `separator` parameter specifies the separator between key and value.

A `comma` separates `key-value` pairs by default, and 

a `colon` separates key and value.

There are no indentations and just newlines are placed if the indent option of json.dumps() is negative, 0 or an empty string. 

if no indent is not there then data can displayed in  a single line


**Example:1** 
```
import json
  

emp_data = '[{"ID":10,"Name":"vamshi","Role":"CEO"},' \
            '{"ID":20,"Name":"nandu","Role":"Editor"}]'

json_object = json.loads(emp_data)

json_formatted_str = json.dumps(json_object)

print(json_formatted_str)
```
output:
```
[{"ID": 10, "Name": "vamshi", "Role": "CEO"}, {"ID": 20, "Name": "nandu", "Role": "Editor"}]
```
**Example2:** `if indent is 5`

```
import json
  
emp_data = '[{"ID":10,"Name":"vamshi","Role":"CEO"},' \
            '{"ID":20,"Name":"nandu","Role":"Editor"}]'

json_object = json.loads(emp_data)

json_formatted_str = json.dumps(json_object, indent=5)

print(json_formatted_str)
```
output:
```
[
     {
          "ID": 10,
          "Name": "vamshi",
          "Role": "CEO"
     },
     {
          "ID": 20,
          "Name": "nandu",
          "Role": "Editor"
     }
]
```

in this example indent is 5 the output displayed after 5 letters space check this program and change the data and try your own.

we can change emp_data in to any other collection of data,like family members,students list with their details or else car names with model,number etc details with this we can easily maintained a data.

## conclusion:

JSON is a format for transferring data from a client to a machine and printing it in a readable format that everyone can comprehend. 