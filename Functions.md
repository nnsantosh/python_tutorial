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
