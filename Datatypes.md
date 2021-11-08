Python lists

A list contains items separated by commas and enclosed within square brackets. All the items belonging to a list can be of different data type.

mylist = [ 'kerala', 257 , 2.23,0, 70.2 ] >>>smalllist = [123, 'university'] >>>print mylist          	        # Prints complete list >>>print mylist[0]       	        # Prints first element of the list >>>print mylist[1:3]     	        # Prints elements starting from 2nd to 4th >>>print mylist[2:]      	        # Prints elements starting from 3rd element >>>print smalllist * 2  	# Prints list two times >>>print mylist + smalllist	# Prints concatenated lists

A tuple is another sequence data type that is similar to the list. A tuple consists of a number of values separated by commas. Unlike lists, tuples are enclosed within parentheses.

The main differences between lists and tuples are: Lists are enclosed in square brackets and their elements and size can be changed but elements and size in tuple cannot be changed. Tuples can be considered as read-only lists.

>>>mytuple = ('kerala', 257, 2.23,0, 70.2)

Now lets have some experiments with list and tupple

>>>mylist = [‘kerala’, 257, 2.23,0, 70.2] >>>mytuple = ('kerala', 257, 2.23,0, 70.2) >>>mylist[2]=0		# changes the third value in list >>>mytuple[2]=0		# Invalid syntax with tuple

Python Dictionary:

Python’s dictionaries work like associative arrays or hashes found in Perl and consist of key-value pairs. Keys can be almost any Python type, but are usually numbers or strings. Values, on the other hand, can be any arbitrary Python object. Dictionaries are enclosed by curly braces.

Key -----------------> value
User Name -------> Password
>>>mydict = {'james bond': '007', 'binary':'zero and one', 'year':2011} >>>mydict['james bond'] >>>mydict['binary'] >>>mydict['year’]

Operators in python

Python also uses similar operators to describe a mathematical operation. Addition, subtraction multiplication and division are described by +, -, *, / respectively. 

Operator      Description

==              Checks if the value of two operands is equal or not, if yes, then condition becomes true

!=              Checks if the value of two operands are equal or not

<>              Checks if the value of two operands are equal or not

>              Checks if the value of left operand is greater than the value of right operand

<              Checks if the value of left operand is less than the value of right operand

>=              Checks if the value of left operand is greater than or equal to the value of right operand

<=              Checks if the value of left operand is less than or equal to the value of right operand

Membership Operators:

One of key the features of Python programming language is that,  it has membership operators, which test for membership in a sequence, such as strings, lists, or tuples. There are two membership operators explained below:

Operator    Description

in             Evaluates to true, if it finds a variable in the specified sequence and false, otherwise.

not in    Evaluates to true, if it does not finds a variable in the specified sequence and false otherwise.

Try the following code

>>>mystring='Hello hai and bye' >>>"hai" in mystring // this will give whether string hai is present in the string str (TRUE or FALSE) >>>mystring.count("hai") // this will count the number of hai present in the string

Identity Operators:

Identity operators compare the memory locations of two objects. There are two Identity operators explained below:

>>> a=5 >>> b=6 >>> c=5 >>> a is b >>> a is c

Input Functions is an interactive built-in function that communicate with user. Try the following command
>>>int= input('Enter an integer : ')
Using this command, user can assign value to variable int 
try

>>> int 