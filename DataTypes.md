##Variable

A variable name must start with a letter or the underscore character
A variable name cannot start with a number
A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
Variable names are case-sensitive (age, Age and AGE are three different variables)

Python allows us to assign values to multiple variables in one line:
x, y, z = "Orange", "Banana", "Cherry"
And we can assign the same value to multiple variables in one line:
x = y = z = "Orange"

Variables that are created outside of a function (as in all of the examples above) are known as global variables.
Global variables can be used by everyone, both inside of functions and outside.
Example to Create a variable outside of a function, and use it inside the function:
x = "awesome"
def myfunc():
  print("Python is " + x)
myfunc()

If you create a variable with the same name inside a function, this variable will be local, and can only be used inside the function. The global variable with the same name will remain as it was, global and with the original value.
Example to Create a variable inside a function, with the same name as the global variable:
x = "awesome"
def myfunc():
  x = "fantastic"
  print("Python is " + x) #output will be "Python is fantastic"
myfunc()
print("Python is " + x) #Output will be "Python is awesome"

## Global variable
Normally, when you create a variable inside a function, that variable is local, and can only be used inside that function.
To create a global variable inside a function, you can use the global keyword.
Example:
def myfunc():
  global x
  x = "fantastic"
myfunc()
print("Python is " + x) #ouput will be "Python is fantastic"

## Data Types

Python has the following data types built-in by default, in these categories:

Text Type:	str
Numeric Types:	int, float, complex
Sequence Types:	list, tuple, range
Mapping Type:	dict
Set Types:	set, frozenset
Boolean Type:	bool
Binary Types:	bytes, bytearray, memoryview

x = 5
y = "John"
You can use following to check the type of variable using type function as shown below:
type(x) will return int



