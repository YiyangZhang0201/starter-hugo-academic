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

This part contains the functions related to converting regression results from Python/Stata to an academic table form.

### Stata to Latex
First, we need to use the pystata package to link the python to STATA.
```{python}
!pip install pystata

import stata_setup
stata_setup.config("C:/Program Files/Stata18/", "mp")
```
 ___  ____  ____  ____  ____ ®
 
 /__    /   ____/   /   ____/      18.0
 
___/   /   /___/   /   /___/       MP—Parallel Edition


 Statistics and Data Science       Copyright 1985-2023 StataCorp LLC
 
                                   StataCorp
                                   
                                   4905 Lakeway Drive
                                   
                                   College Station, Texas 77845 USA
                                   
                                   800-STATA-PC        https://www.stata.com
                                   
                                   979-696-4600        stata@stata.com

Stata license: Unlimited-user 2-core network, expiring  8 Aug 2024

Serial number: 501809315448

  Licensed to: Scheller College of Business
               GT

Notes:
      1. Unicode is supported; see help unicode_advice.
      2. More than 2 billion observations are allowed; see help obs_advice.
      3. Maximum number of variables is set to 5,000 but can be increased;
          see help set_maxvar.

A successful link should show the above result in the notebook. You must edit your path and version to suit your STATA on the machine.

I will use following data as an example:
```{python}
%%stata
sysuse auto, clear
```

