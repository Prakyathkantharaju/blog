---
layout: page
title: "Install and setup"
permalink: python/note1
---


# Overview
- Install
- Setup
- Variables


## Install

### Window and mac:
There are multiple ways to install python in windows. Two most popular methods are
1. [Anaconda](https://docs.anaconda.com/anaconda/install/index.html)
2. [python.org](https://www.python.org/downloads/)


> I prefer the conda install for the windows. Its very easy to setup and get started.
> Also please make sure you enable all user access to the installation.


### Linux
Most linux has python install if not install using python.org link above.


## Setup
Open the cmd or powershell in windows or terminal in mac os or linux, then type
```
python
```
if you have installed the everything correctly you should not get any error
and you should get a command prompt.

Type the following command in the prompt.

```
>>> print('Hello world')
```
you should see a Hello world in the prompt.

## What is python?
python in is an interputted programming language, that means unless mentioned python commands
are commanded line by line. Ofcourse there are exceptions to this rule. Generally you can combine the
the commands in a script file. The generally file extenstion for the python file is _.py_

## How does syntax of python code looks like ?
Here in an example of the python file
```
# test.py
print('hello world')

X = 0
Y = [0,1,2,3,4,5,6,7,8,9]
Z = 0.1

for i in Y:
    print(i)
```
- print:As any other programming language python offers a method to output the values to the command prompt or terminal
- X: X is the variable. It is storing the value 0 and the type of the variable is int.
- Y: Y is the list. List can be considered as a less prowerful array.





