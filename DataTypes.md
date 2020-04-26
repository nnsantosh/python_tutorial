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

### String(str in python)

String can be single quote or double quote: <br/>
y = "John" <br/>
y = 'John' <br/>

String interplolation or formatting: <br/> 
print("My Name is {}, my id is {}".format('Santosh',10)) <br/>
Output will be : My Name is Santosh, my id is 10 <br/>

print("First: {x} Second: {y}".format(x='XXX',  y='YYY')) <br/>
Output will be: First: XXX Second: YYY <br/>

Some useful methods of String: <br/>
y.tolower() <br/>
y.split() <br/>


### Float number (float in python)

x = 10.0 <br/>

### Complex number (complex in python)

z = 1 + 2j <br/>
The complex number has two parts – real and imaginary. The imaginary part is denoted with “j” suffix. <br/>

### List (list in python)

listOfNum = [1,2,3] <br/>
listOfStr = ['a','b','c'] <br/>
listOfMixedDataTypes = [1, 'a', 10.0] <br/>

We can use indexing to grab elements from list: <br/>
ex: mylist = [1,2,3] <br/>
mylist[0] = 1 <br/>
mylist[2] = 3 <br/>
Another way of grabbing the last element of list is using negative indexing as shown: <br/>
mylist[-1] = 3 <br/>
 
You can modify the element of list <br/>
Example: mylist[0] = 4 <br/>

To add an element to a list: <br/>
Example: mylist.append(5) <br/>

We can also use nested lists(list having another list as element)" <br/>
Example mylist = [1,2.[100,200]] <br/>
To grab element 200 we can use mylist[2][1] <br/>

### Pop something of a list
 mylist = [1,2,3] <br/>
 To remove last element of the list <br/>
 last = mylist.pop() <br/>
 print(mylist) Output will be [ 1,2] <br/>
 print(last) Output will be 3  <br/>
 
 By default last element of list is popped of the list. But we can indicate specifically which element to pop using index of element: <br/>
 mylist.pop(0) <br/>
 
### To check if element present in list
1 in [1,2,3] <br/>
Output will be True <br/>
 
### Dict (dict in python)

Similar to map in other languages. <br/>
myDict = {'key1':'value1','key2':'value2'} <br/>
To access value1 use myDict['key1'] <br/>

### To grab all keys: <br/>
myDict.keys() <br/>
Output will be dict_keys(['key1', 'key2']) <br/>

### To grab items:  <br/>
myDict.items() <br/>
Output will be dict_items([('key1', 'value1'), ('key2', 'value2')]) <br/>
Notice the output is tuple elements <br/>

### Boolean (bool in python)

Boolean value is either True or False <br/>
myBoolVar = False <br/>

### Tuples (tuple in python)

myTuple = (1,2,3) <br/>
Similar to list but they are immutable <br/>
Accessing element of tuple will be similar to accessing list element: <br/>
myTuple[0] will return 1 <br/>

### Set (set in python)

Is an unordered collection of unique elements. <br/>
mySet = {1,2,3} <br/>











