---
layout: post
title: "Notes on Python Programming"
date: 2018-01-16
comments: true
categories: [home,notes]
abstract: "[Updating] About Python Programming"
---
> <small>Notes on Python Programming </small>

### Python Data Model -> A Framework/API for core language constructs

Python interpreter invokes special methods to perform basic object operations.

By using and implementing **special methods of Python Data Model** in your objects, your objects can **behave like the built-in types**, enabling the expressive coding style **Pythonic**.

#### Data Sturctures
  * sequences - Python sequences are often categorized as **mutalbe or immutable**, and also could be considered as **flat sequences and container sequences**.
    + container sequences -> hold **references** to the objects
    + flat sequences (like str, bytes) -> more compact because of the physically store the value
    + 
    + **list** -> mutable and mixed-type
      - list comprehensions and generator expression

    + **tuples** -> immutable lists
      - tuples can hold records
      - tuple unpacking -> parallel assignment

    + array -> efficient because of only **the packed bytes for numeric data**
      - for large sequences of numbers, this saves a lot of memory
      - NumPy lib
  
  * dict and set
    + **hash tables** are the engines for the high performance dicts
    + hash tables must be sparse to work, they are **not space efficient**
  
  * str versus bytes

#### Functions as objects
  * Functions, like integers, strings, and dictionaries, also can be a **program entity**, this enables programming in a **functional style**.



  
#### Object Oriented


#### Control flow  
  * Concurrency 


#### Metaprogramming 


### Rust language

### Notes
 * Reload modules problem in Emacs Python Shell
   - use importlib to reload(models) 
   - or use ipython and  %autoreload

 * virtualenvs setup for python3 -> pipenv
   - New a project: >pipenv --python 3.6
   - Install all dependencies:  >pipenv install
   - Locate the virtualenv: >pipenv --venv
   - Use the shell: >pipenv shell
   - Uninstall everything:  >pipenv uninstall --all

 * <del>Your environment contains PYTHONPATH=/usr/local/lib/python2.7/site-packages
This doesn't work with Python 3 for obvious reasons. To remove it:
> unset PYTHONPATH </del>


#### reference
* Fluent python