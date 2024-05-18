---
title: Personal Package Introduction
authors:
- Yiyang Zhang
tags: []
categories: []
projects: []
date: "2024-05-17T00:00:00Z"
image:
  caption: ""
  focal_point: ""
---

This is the personal package I built for academic research convenience. I will update it regularly and add more useful functions. You can download it through pip install if you think it is helpful.

# Table of contents
1. [How to Setup](#Setup)
2. [Functions](#Functions)
    1. [File Operation](#fileop)
    2. [Regression Result Convert](#regconv)

# How to Setup <a name="Setup"></a>

Please ignore the version number shown in the featured figure and use the following code to set it up.

```{python}
pip install yiyangzhang0201
import yiyangzhang0201
```

# Functions <a name="Functions"></a>
## File Operation <a name="fileop"></a>

This part contains the functions related to file operations.

```{python}
from yiyangzhang0201.fileop import *

get_subfolders(parent_path)
get_files(folder_names)
create_new_folder(path)
copy_file(file_path, new_fold)
```
The functions included are:
* Get subfolders under a folder and return a list containing all the subfolders.
* Get all the files under a folder and return a list containing all the files.
* Create a new folder if it does not exist.
* Copy a file to the given folder; if the folder does not exist, create it.

## Regression Result Convert <a name="regconv"></a>

This part contains the functions related to converting regression results from Python to an academic table form.
