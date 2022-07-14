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
