## Functions

Function without parameter: <br/>
def myFunc(): <br/>
&nbsp;&nbsp;&nbsp;&nbsp;print("hello") <br/>
    
myFunc() <br/>
Output will be hello <br/>

If you pass parameter to function: <br/>

def myFunc(name): <br/>
&nbsp;&nbsp;&nbsp;&nbsp;print("hello "+name) <br/>
    
myFunc("Santosh") <br/>
Output will be hello Santosh <br/>

If you want to invoke a function with parameter by not specifying parameter at the time of invocation you can use default argument: <br/>
def myFunc(name="No NAME"): <br/>
&nbsp;&nbsp;&nbsp;&nbsp;print("hello "+name) <br/>
    
myFunc() <br/>
Output will be hello NO NAME <br/>

### Documentation string or docstring is like multiline comments to describe the function as shown below:

def myFunc(name="No NAME"): <br/>
&nbsp;&nbsp;&nbsp;&nbsp;''' <br/>
&nbsp;&nbsp;&nbsp;&nbsp;This prints out the user name <br/>
&nbsp;&nbsp;&nbsp;&nbsp;''' <br/>
&nbsp;&nbsp;&nbsp;&nbsp;print("hello "+name) <br/>

myFunc() <br/>
Output will be hello NO NAME <br/>

### Function returning value

def squareFunc(num):  <br/>
&nbsp;&nbsp;&nbsp;&nbsp;return num**2  <br/>
    
result = squareFunc(4)  <br/>
print(result)  <br/>

Output will be 16  <br/>

## Lambdas

Syntax: lambda arguments : expression <br/>
Consider below function: <br/>
def x(a): <br/>
&nbsp;&nbsp;&nbsp;&nbsp;return a + 10 <br/>

This can be written as: <br/>
x = lambda a : a + 10 <br/>
print(x(5)) <br/>
Output will be 15 <br/>

### Why Use Lambda functions
The power of lambda is better shown when you use them as an anonymous function inside another function. <br/>
Say you have a function definition that takes one argument, and that argument will be multiplied with an unknown number: <br/>
def myfunc(n): <br/>
&nbsp;&nbsp;&nbsp;&nbsp;return lambda a : a * n <br/>

Use that function definition to make a function that always doubles the number you send in: <br/>
mydoubler = myfunc(2) <br/>
mydoubler(5) Output will be 10 <br/>
Use that function definition to make a function that always triples the number you send in: <br/>
mytripler = myfunc(3) <br/>
mytripler(5) Output will be 15 <br/>


