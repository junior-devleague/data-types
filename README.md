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
myList = [1, 2.3, "string"]
myList[0] = 1
myList[1] = 2.3
myList[2] = "string"
```

##### Related Functions:
Function | Description
list\[i] | returns the value of list at i.
len(list) | returns the length of the list.
list.append(val) | adds *val* to the end of *list*.
list.insert(i, val) | adds *val* to index value *i* of *list* pushes everything at an index value >= i one to the right.
list\[i] = val | *replaces* the item at index value *i* with *val*.

There are many more functions related to lists, but these are the basics.

#### Tuples:
A tuple is almost exactly the same as a dictionary -- it is also stores multiple items and gets said items using an index value, however aside from the syntax (lists are enclosed in square brackets \[], tuples are enclosed in parentheses ())there is one *huge* difference between the two -- Lists are mutable, tuples are not. *Mutability* is the ability for something to be changed. Something is said to be *mutable* if you can change things about it after it's been created, or said to be *immutable* if you cannot. With lists, you can add new items, take old items away, change what the value is at a certain index value, or do any number of other things after it's been created, but with a tuple, once it's been made, that's how it's going to be forever. You can't add values, you can't take values away, you simply can't change it.

##### Related Functions:
Function | Description
---------|------------
tuple\[i] | returns the value of tuple at i.
len(list) | returns the length of the tuple.

As you can see, much more limited than lists. However, there are situations where you don't *want* a set of data to be changable, in which case you'd want to use a tuple instead of a list

#### Dictionaries:
Dictionaries are similar to lists in that they store multiple items, but that's about the extent of the similarities. Dictionaries, unlike lists and tuples, *do not* use index value to get individual items. Instead, they contain sets of what are known as *key/value pairs*, contained within curly braces {}. A key/value pair is, like the name implies, a pair of a *key* and a *value*. A dictionary is composed of pairs of keys & values separated with colons, with each pair being separated by commas. Both keys and values can be any type of variable -- strings, ints, floats, you name it. The only stipulation is that you *cannot* have 1 key that is associated to 2 values. Similar to functions that you've learned in math, two inputs can have the same output, but one input *cannot* have 2 outputs (real functions at least). If you could have 2 outputs that came from one input, how would python know which output you want at a given moment?
Ex:
```
myDict = {'Alice': 16, 'Bob': 17.5, 18: 'Sylvie', 16.5: 'Stephen'}
myDict['Alice'] = 16
myDict['Bob'] = 17.5
myDict[18] = 'Sylvie'
myDict[16.5] = 'Stephen'
```

##### Related Functions:
Function | Description
---------|------------
dict\[key] | returns the related value of key.
len(dict) | returns the length of the dict.
dict\[key] = val | Sets the value associated with key equal to val. If the pair already exists, the old value is replaced. If it doesn't exist, it's created with a value of val
dict.keys() | gets a list of all the keys from the key/value pairs in the dict. However, you need to surround it with list() to be able to save it as a list.
dict.values() | gets a list of all the values from the key/value pairs in the dict. However, you need to surround it with list() to be able to save it as a list.

As you can see, the majority of the related functions are very different, and even the similar ones are not quite the same.
