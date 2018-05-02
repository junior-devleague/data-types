---
author:
- Somewha7
title: 'working title'
type: Lesson / Activity
---

Summary
=======

Lesson about lists, tuples, dictionaries, and related functions

Objective
=========

-   Learn about storing data in lists and dictionaries
-   Learn the differences and individual uses for lists and dictionaries
-   Learn built-in functions related to lists and dictionaries

Prerequisites
=============

-   Basic usage of Python REPL
-   Knowledge of the basic variable types in python (strings, integers, floats)

Concepts
============

#### Lists:
A list is used to store multiple strings, integers, or floats in a single variable. A list stores those values inside of square brackets [], with each value separated by commas. A value is called from a list using an *index value*. Index value is what is used to retrieve an individual value from a list. Index value runs from 0 to the length of the list minus 1. for example in a list of 3 items, index value would run from 0 to 2. You use the index value by writing the list name followed by the index value in more square brackets.
Ex: 
```
myList = ['a', 'b', 'c']
myList[0] = 'a'
myList[1] = 'b'
myList[2] = 'c'
```

#### Dictionaries:


Desired Outcomes
================

-   Basic understanding of while loops in python
-   Usage of loops that will run an indeterminate amount of times
-   When to use while loops vs. for loops

Tasks
=====

1.   Create a file music.py, or create a new REPL in repl.it
2.   Create an empty list, and make a variable with a value of True
3.   Create a while loop that will run **while** your variable is True
4.   Ask the user for an input, store it as a variable, and use that to determine whether to exit the loop or to add a song.
5.   **if** they're done adding songs, set your variable with a value of True to False, and the loop will end
6.   ***else*** add their input to the empty list you created outside the loop

### Choto Stretch Goals
-   make a function that will print out "Now playing <song name>" for each of the songs in your list.
-   put the while loop in a function so that you can call on it at will, or import it into another python program!
-   figure out a way to shuffle the list so that your friend won't have to listen to the same songs in the same order all the time.
-   make the program shuffle the playlist everytime your friend listens to it so that you don't have to shuffle it for them!
-   encrypt the list of songs so that nobody will know what kind of music you and your friend like to listen to.
