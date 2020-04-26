## Variable

A variable name must start with a letter or the underscore character. <br/>
A variable name cannot start with a number. <br/>
A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ ) <br/>
Variable names are case-sensitive (age, Age and AGE are three different variables) <br/>

Python allows us to assign values to multiple variables in one line: <br/>
x, y, z = "Orange", "Banana", "Cherry" <br/>
And we can assign the same value to multiple variables in one line: <br/>
x = y = z = "Orange" <br/>

Variables that are created outside of a function (as in all of the examples above) are known as global variables. <br/>
Global variables can be used by everyone, both inside of functions and outside. <br/>
Example to Create a variable outside of a function, and use it inside the function: <br/>
x = "awesome" <br/>
def myfunc(): <br/>
  print("Python is " + x) <br/>
myfunc() <br/>

If you create a variable with the same name inside a function, this variable will be local, and can only be used inside the function<br/>  
The global variable with the same name will remain as it was, global and with the original value. <br/>
Example to Create a variable inside a function, with the same name as the global variable: <br/>
x = "awesome" <br/>
def myfunc(): <br/>
  x = "fantastic" <br/>
  print("Python is " + x) #output will be "Python is fantastic" <br/>
myfunc() <br/>
print("Python is " + x) #Output will be "Python is awesome" <br/>

## Global variable
Normally, when you create a variable inside a function, that variable is local, and can only be used inside that function. <br/>
To create a global variable inside a function, you can use the global keyword. <br/>
Example: <br/>
def myfunc(): <br/>
  global x <br/>
  x = "fantastic" <br/>
myfunc() <br/>
print("Python is " + x) #ouput will be "Python is fantastic" <br/>

## Data Types

Python has the following data types built-in by default, in these categories: <br/>

Text Type:	str <br/>
Numeric Types:	int, float, complex <br/>
Sequence Types:	list, tuple, range <br/>
Mapping Type:	dict <br/>
Set Types:	set, frozenset <br/>
Boolean Type:	bool <br/>
Binary Types:	bytes, bytearray, memoryview <br/>

x = 5 <br/> 
y = "John" <br/>
You can use following to check the type of variable using type function as shown below: <br/>
type(x) will return int <br/>



