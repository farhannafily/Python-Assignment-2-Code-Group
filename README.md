# Tugas-2-Python-Kelompok-Code

**Collection Data Types**
There are four collection data types in the Python programming language:

1. List is a collection which is ordered and changeable. Allows duplicate members
2. Tuple is a collection which is ordered and unchangeable. Allows duplicate members.
3. Set is a collection which is unordered, unchangeable*, and unindexed. No duplicate members.
4. Dictionary is a collection which is ordered** and changeable. No duplicate members.

**List**
Lists are the most versatile of Python's compound data types.

Lists are used to store multiple items in a single variable.

A list contains items separated by commas ( , ) and enclosed within square brackets [ ].

**Append Items**
To add an item to the end of the list, use the append() method:

**Extend List**
To append elements from another list to the current list, use the extend() method.

**Insert**
The list insert is a built-in Python function that inserts an item to the list at the given index. The insert method accepts index and element as arguments and does not return any value, but it inserts the given element at the given index.

Syntax : list.insert(index, element)

**Remove**
To remove an element from the List in Python, use the List.remove method. The List remove is a built-in method that searches for the element in the List and removes the first matching item. The remove method does not return any value but removes the given object from the List.

Syntax : list.remove(item)

**Del**
In Python everything is an object, so the keyword can also be used to delete variables, lists, or parts of a list etc.

Note : One thing to remember that while removing the elements, it counts the start index but not the end index. The last removed element's index is end index – 1. It does not include the end index.

Syntax : del list[start index: end index]

**POP**
pop () function is used to remove an element in the list (by default the last element), and returns the value of that element.

**INDEX**
The index() function is used to find the position of an element in an array list.

**Count**
Python List count() is a function in Python that returns the count of how many times a given element occurs in a List. The count() function is used to count elements on a list as well as a string.

Syntax : list.count(element)

Parameter : element (required) - Any type (string, number, list, tuple, etc.), the element to search for

Return : count() method returns the count of how many times element occurs in the list

Exception : If more than one parameter is passed in count() method, it returns a TypeError.

**LEN**
LEN is used to return the number of items in an object

**sort()**
sort() is used to help sort the disordered list

**reverse()**
reverse() is used to sort list in a descending manner based on the predetermined order

**Slicing**
Slicing in python is a technic to slice some of object in dataset. Slicing can be done in many type of dataset like string, tuple, list, or range.

**Tuple**
Tuple is data type in python which is ordered and can't be changed. Tuple are written by round bracket. Tuple is faster than list, set, or dictionary because the order is fixed

**Set**
Set is unordered data types in python. This mean you can't get the data from set by slicing it. Set element are unique. Set are written by curly bracket.

**Dictionary**
Dictionary in Python is an unordered collection of data values, used to store data values like a map, which, unlike other Data Types that hold only a single value as an element, Dictionary holds key:value pair. Key-value is provided in the dictionary to make it more optimized.

Note: Keys in a dictionary don’t allow Polymorphism.

**Conversion**
Data type conversion is a technique of changing the initial value of data type a, to data type b.
