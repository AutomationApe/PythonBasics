# PythonBasics
Documenting the basics of Python as I progress in the language

Python is a high-level interpreted general purpose programming language. 
The highlight for Python is the fact that it promotes increased productivity thanks to its simple syntax.
Python is used in practically all facets of development: from Web Development to Machine Learning.

Python Built-in Data Types:

	Numeric: int, float, complex

	Text: str

	Sequence: list, tuple, range

	Mapping: dict

	Set: set, frozenset

	Boolean: bool

	Binary: bytes, bytearray, memoryview

	None: NoneType

Setting variables of each data type:

	x = "Hello World" (str)

	x = 20    (int)

	x = 20.5  (float)

	x = 1j    (complex)

	x = ["apple", "banana", "cherry"] (list)

	x = ("apple", "banana", "cherry") (tuple)

	x = range(6)  (range)

	x = {"name": "John", "age": 35}   (dict)

	x = {"apple", "banana", "cherry"} (set)

	x = frozenset({"apple", "banana", "cherry"})  (frozenset)

	x = True  (bool)

	x = b"Hello"  (bytes)

	x = bytearray(5)  (bytearray)

	x = memoryview(bytes(5))  (memoryview)

	x = None  (NoneType)
	
Link to Repl.it project demonstrating data types in python:
https://replit.com/@PythonicPelican/DataTypes#main.py

Basic Math Functions:

	math.ceil() - rounds a number up to the nearest integer
	
	math.fabs() - returns the absolute value of a number
	
	math.floor() - rounds a number down to the nearest integer
	
	math.gcd() - returns the greatest commond divisor of two integers
	
	math.pow() - returns the value of x to the power of y
	
	math.sqrt() - returns the square root of a number
	
Link to Repl.it project demonstrating basic math functions in python:
https://replit.com/@PythonicPelican/BasicMathFunctions#main.py


Variables:
	
	Variables are symbolic names for an object in memory. This can be an integer value being stored or a string message, etc.
	
	Variables in python typically follow snake_case; ex: first_name = "John"
	
	Variables must start with a lowercase letter or an underscore
	
	Variables can contain letters, numbers, and underscores
	
	Variables are case sensitive; ex: first_name != first_Name
	
	Variables should not overwrite keywords; ex: Print = "blahblahblah" 
	
	Variables can be created as constants by writing them in all caps; ex: PI = 3.14
	

Augmented Assignment Operators:

	Augmented Assignment Operators are useful for quickly completing addition, subtraction, multiplication, and division operations.
	
	Addition - "+="; ex: number += 5
	
	Subtraction - "-="; ex: number -= 5
	
	Multiplication - "*="; ex: number *= 5
	
	Division - "/="; ex: number /= 5
	
Link to Repl.it project demonstration augmented assignment in python:
https://replit.com/@PythonicPelican/AugmentedAssignment#main.py



Strings:

	Strings are a data type that hold multiple characters. A string of text.
	
	Strings can represent words, whole sentences, or even paragraphs through the use of multiline strings (example in Repl.it)
	
	Strings can also be added to eachother through string concatenation (example in Repl.it)
	
Link to Repl.it project demonstrating multiline strings and string concatenation:
https://replit.com/@PythonicPelican/Working-with-strings#main.py


Type conversion:

	You can change the data type of a value through the use of type conversion; ex: text = str(5)

Link to Repl.it project demonstrating basic type conversion:
https://replit.com/@PythonicPelican/TypeConversion#main.py


Escape characters:

	In programming, there are escape characters that can help with formatting strings.
	
	\n - new line
	
	\t - inserts a tab
	
	\' or \" - allows for single or double quotes to be recognized as a character in the string
	
	\\ - allows for backslashes to be recognized as a character in the string

Link to Repl.it project demonstrating common escape characters:
https://replit.com/@PythonicPelican/EscapeCharacters#main.py

Formatting strings with variables:
	
	Variables in strings can be formatted in a variety of ways
	
	You could use f-strings; ex: print(f"{name}")
	
	You could use the format() method (example in Repl.it)
	
	You could use concatenation; ex: message = name + " is a great person!"

Link to Repl.it project demonstrating some string formatting techniques:
https://replit.com/@PythonicPelican/FormattingStrings#main.py

String index:

	Strings are essentially an array (collection) of characters
	
	You can call individual characters from a string using its index. In Python, the first letter has an index of [0]
	
	For example, the word "hello" would have h at index [0], e at index[1], l at index [2], and so on.
	
Link to Repl.it project demonstrating string index usage:
https://replit.com/@PythonicPelican/StringIndex#main.py

Common built-in functions:

	Python comes equipped with built-in functions that can do a number of different things.
	
	For example, the len() function will iterate over an object and return the number of items inside of it
	
To find out more about built in functions:
https://docs.python.org/3/library/functions.html


Booleans:

	Booleans are data types that are based on boolean algebra and essentially boil down to true or false.
	
	Booleans are expressions that either equal 0 (false) or 1 (true) when computed and are powerful tools for conditions.
	
	For example, you can set code to be executed only when a condition equals true; if (today_is_birthday == true)
	
For more information on booleans:
https://www.w3schools.com/python/python_booleans.asp


Lists:

	Lists are ordered sequences of objects of any type. They are a kind of array
	
	Lists are useful for storing a collection of items; ex: fruits = ["apple", "banana", "cherry"]
	
	Lists are one of many data structures, which are important concepts as they allow for us to store data in a container and use the data within the container in many different ways.
	
	You can access items within a list using their index, ex: fruits[0] would produce "apple", fruits[1] would produce "banana"
	
	You can slice through lists
	
	Unlike with strings (which are immutable and cannot be changed after declaration), lists are mutable.
	ex: fruits[2] = "pear" would make the list fruits now contain "apple", "banana", and "pear"
	
For more information on lists:
https://www.w3schools.com/python/python_lists.asp

Matrix:

	A matrix is a 2-dimensional list, in other words, it is a list that contains a list.
	ex:
	
	food = [
	         ["hotdog", "burger", "pizza"],
		 ["apple", "banana", "pear"],
		 ["carrot", "brocolli", "peas"]
	       ]
	      
	In order to access an object from the list, you can call it like this: food[0][1] -> produces "burger"
	The first index selects the first list, and the second index calls the item within the first list.
	
Link to Repl.it project demonstrating matrices:
https://replit.com/@PythonicPelican/FoodMatrix#main.py

List Methods:

	There are many methods that can be used to alter lists.
	
	For example, the append() method is used to add an item to a list.
	ex: fruit.append("watermelon") would produce -> ["apple", "banana", "pear", "watermelon"]
	
	Another example would be the insert() method, which adds an item to a list at a specific index.
	ex: fruit.insert(2, "mango") would produce -> ["apple", "banana", "mango", "pear", "watermelon"]
	
For more information on list methods:
https://www.w3schools.com/python/python_lists_methods.asp


List Unpacking:

	List unpacking is a useful technique that enables us to assign variables to items in a list in one declaration.
	ex: a, b, c = [1, 2, 3] -> print(a) would output: 1, print(b) would output: 2, etc.
	
	You can also slice a list through unpacking.
	ex: a, b, c, *other, d = [1, 2, 3, 4, 5, 6, 7, 8, 9] -> print(a) outputs: 1, print(c) outputs: 3, print(other) outputs: [4, 5, 6, 7, 8], and print(d) outputs: 9
	
For more information on unpacking lists:
https://www.pythontutorial.net/python-basics/python-unpack-list/

Dictionaries:

	A data type in Python which is also a data structure. Enables us to store data as a set, using a key-value pair. 
	ex: dictionary = {
	                    'a': 1,
			    'b': 2
			 }
			 
	dicts can be accessed as follows: print(dictionary['b']) -> outputs: 2
	
	What if we store a list in the dict?
	ex: my_list = [
			{
		          'a': [1, 2, 3],
			  'b': "hello",
			  'c': True
			}
		       ]
	We could access the list as follows: print(my_list[0][1]) -> outputs: 2
	
	*keys MUST be IMMUTABLE and UNIQUE*
	
For more information on dictionaries: 
https://www.w3schools.com/python/python_dictionaries.asp

Understanding data structures:

	There are many reasons that can help decide whether you should use a dictionary or a list and practice helps the process
	of making these decisions.
	
	However, there are things to consider such as the fact that lists allow for duplicate entries while dictionaries do not. 
	Dictionaries will instead overwrite values for keywords. Lists on the other hand will simply store the duplicate.
	
	Food for thought...
	
Dictionary Methods:

	Like lists, there are useful methods that you can use to perform actions in Python.
	
	For example, the get() method allows you to search for a key in a dictionary and set a default value if it
	doesn't exist.
	ex:
		user = { 
			 'basket': [1, 2, 3],
			 'greet': 'hello',
			 'age': 20
		       }
		 
		print(user.get('age', 55)) -> outputs 55 if 'age' does not exist in the dictionary, otherwise outputs the value of 'age'
	
	Here are a few other useful methods for working in the dictionary:
	
	keys() - checks the keys in the dict
	
	values() - checks the values in the dict
	
	items() - checks the key-value pairs in the dict
	
	clear() - erases all content in the dictionary
	
	pop() - removes a key and returns the value that it was associated with
	
	popItem() - removes the last key-value pair in a dict
	
	update() - updates a key-value pair
	
For more information on dictionary methods:
https://www.w3schools.com/python/python_dictionaries_methods.asp

Tuples:

	Another data type in Python, that is also a data structure.
	Tuples are like lists, except they are immutable.
	
	my_tuple = (1, 2, 3, 4, 5)
	
	Once this has been set, you cannot modify it outside of its declaration. It cannot be sorted, reversed, etc. 
	
	my_tuple[1] = z -> errors out as a tuple is immutable and cannot be altered.
	
	You can access tuples through the index of their items just like lists.
	
	Tuples are very useful for lists that will not change.
	
	Real world example for tuples could be coordinates for a location as the location does not change.
	
	Tuples have few methods, primarily count() and index().
	count() is used to return how many times an item appears in a tuple.
	index() is used to find the index of an item in the tuple.
	
	*when using items() method on a dict, the key-value pairs are returned as tuples*

Sets:

	Sets are unordered collections of unique objects.
	Sets are another data structure.
	
	my_set = {1, 2, 3, 4, 5, 5}
	
	print(my_set) -> outputs: {1, 2, 3, 4, 5}
	
	Now where is the other 5? Remember, sets care about UNIQUE values, so the duplicate 5 is omitted.
	
	Sets are powerful as they can be used to return a list of only unique values.
	ex: 
	
		my_list = [1,1,2,2,3,3,4,4,5,5,6,5]
		
		print(set(my_list)) -> outputs: {1, 2, 3, 4, 5, 6}
		
	A real world example of sets' usefulness is a website collecting usernames or emails, it needs to make sure there are no duplicates,
	therefore saving the usernames/emails to a set would ensure we are checking for unique values and eliminating duplicates.
	
For more information on sets:
https://www.w3schools.com/python/python_sets.asp

Set methods:

	The real power of sets comes out when used with methods.
	These methods include:
	
	difference()
	discard()
	difference_update()
	intersection()
	isdisjoint()
	issubset()
	issuperset()
	union()
	
	ex:
	
	my_set = {1,2,3,4,5}
	your_set = {4,5,6,7,8,9,10}
	
	print(my_set.difference(your_set)) -> outputs: {1,2,3} as that is what is different between the two sets
	
	my_set.discard(5) -> removes 5 from my_set
	
	print(my_set.difference_update(your_set)) -> outputs: {1,2,3} as it alters my_set to consist of only the items that differ from your_set 
	
	print(my_set.intersection(your_set)) -> outputs: {4,5} as these are the items that are simlar in both sets
	
	print(my_set.isdisjoint(your_set)) -> outputs: False as the two sets have common items (4 and 5)
	
	issubset() -> outputs: True if the entirety of a set can be found within another
	
	issuperset() -> outputs: True if the set invoking the method encompasses the target set
	
	print(my_set.union(your_set)) -> outputs: {1,2,3,4,5,6,7,8,9,10} as this creates a new set consisting of both sets combined with only unique values
	
	*shorthands exist for intersection() and union().
	*union() -> print(my_set | your_set) -> outputs: {1,2,3,4,5,6,7,8,9,10}
	*intersection() -> print(my_set & your_set) -> outputs: {4,5}
	
For more information on set methods:
https://www.w3schools.com/python/python_sets_methods.asp
	
	
	
	
	
	



