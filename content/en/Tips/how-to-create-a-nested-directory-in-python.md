---
title: "How to create a Safely Nested Directory in Python"
description: "Depending on the version of Python you're using, there are several ways to create a nested directory"
date: "2023-01-10T12:00:00+09:00"
draft: false
link: "Nested Directory in Python"
author: "harika"
---

## How to create a Safely Nested Directory in Python
Depending on the version of Python you're using, there are several ways to create a nested directory. 

## 1. using os.makedirs

1. To create a nested directory in Python, you can use the `os module`.
2. You can also use the `os.makedirs()` function to create intermediate directories as needed. 
3. Remember that the `os.makedirs(`) function requires you to have the appropriate permissions in order to create directories in the specified location. 
4. For older Python versions `os.path.makedirs` can be used together with 
`os.path.exists`.


## Example : using `os.makedirs`

```Python
import os

# Create a new directory
os.makedirs('existing/new/nested/directory', exist_ok=True)
```
This will create the `directory` directory, as well as the nested and new directories if they don't already exist. The `exist_ok` parameter specifies that `it's okay` if the directories already exist and prevents the function from raising an error.

## 2. Using pathlib.Path.mkdir 

For Python 3.5 and above, you can use pathlib.Path.mkdir to create a nested directory.

## Example : Using pathlib.Path.mkdir 

```Python
from pathlib import Path
Path("/root/dirA/dirB").mkdir(parents=True, exist_ok=True)
```

1. Import class Path from pathlib library.

2. Call the module `mkdir()` with two arguments 
   1.parents 
   By default, `parents is set False`. In this case, if the parent directory is not present, then `FileNotFoundError` is thrown. 
   For example, if you want to create a nested directory /folder1/folder2/folder3, and folder1 (parent) does not exist already, then `FileNotFoundError` is raised by default. So, we can set
   `parents is set True`.

   2.exist_ok
   By default`exist_ok is False`. 
   If the directory already exists,FileExistsError is raised. 
   `exist_ok is True `to prevent this error.

3. The `pathlib` module is also very useful to check if a file or a directory exists in Python.

## 3. Using distutils.dir_util

`mkpath` creates the nested directory, and does nothing if the directory already exists. This works in both Python 2 and 3.
 
## Example :  Using distutils.dir_util

```Python
import distutils.dir_util
distutils.dir_util.mkpath(path)
```

If you use 'mkpath' to create a directory, delete it from Python or another programme, and then use mkpath to create the same directory again.

mkpath will simply use its incorrect cached information of having previously created the directory and won't actually create the directory again.
As opposed to this, 'os.makedirs' doesn't rely on any kind of cache.
This restriction might be acceptable for some applications. 

## Example : one more example distutils.dir_util.mkpath

```Python
import distutils.dir_util

distutils.dir_util.mkpath("/root/dirA/dirB")
```
You should provide the full path (absolute path) of the directory (not the relative path). If the directory already exists, the above code does not raise an exception.

## Summary
In this tutorial we learnt about creation of Nested Directory in Python, 
in a best way with simple examples.