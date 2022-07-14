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
