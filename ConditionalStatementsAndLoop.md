## if statement in python

if 1 == 1: <br/>
&nbsp;&nbsp;&nbsp;&nbsp;print("oh yeah!") <br/>
    
Output will be oh yeah! <br/>

## if else statement in python

if 1 == 2: <br/>
&nbsp;&nbsp;&nbsp;&nbsp;print("worked") <br/>
else: <br/>
&nbsp;&nbsp;&nbsp;&nbsp;print('nope!') <br/>
    
Output will be nope! <br/>
    
## elif statement

if 1 == 2: <br/>
&nbsp;&nbsp;&nbsp;&nbsp;print("worked") <br/>
elif 3 == 3: <br/>
&nbsp;&nbsp;&nbsp;&nbsp;print('second condition true!') <br/>
else: <br/>
&nbsp;&nbsp;&nbsp;&nbsp;print('nope!') <br/>

Output will be second condition true! <br/>

## for loop

mylist = [1,2,3,4] <br/>
for item in mylist: <br/>
&nbsp;&nbsp;&nbsp;&nbsp;print(item) <br/>
Output will be: <br/>
1<br/>
2<br/>
3<br/>
4<br/>

## while loop

i = 1 <br/>
while i < 4: <br/>
&nbsp;&nbsp;&nbsp;&nbsp;print("i is {}".format(i)) <br/>
&nbsp;&nbsp;&nbsp;&nbsp;i = i + 1 <br/>
Output will be: <br/>
i is 1 <br/>
i is 2 <br/>
i is 3 <br/>

## range

mylist = [0,1,2,3,4] <br/>
The same list can be created using range as shown below: <br/>
list(range(0,5)) <br/>

## List comprehension

Consider below for loop: <br/>
mylist = [1,2,3,4,5] <br/>
mySquaredList = [] <br/>
for num in mylist: <br/>
&nbsp;&nbsp;&nbsp;&nbsp;mySquaredList.append(num ** 2) <br/>
print(mySquaredList) <br/>
Output will be: [1, 4, 9, 16, 25] <br/>

Same thing can be achieved using: <br/>
mylist = [1,2,3,4,5] <br/>
mySquaredList = [ num**2  for num in mylist ] <br/>
print(mySquaredList) <br/>
Output will be: [1, 4, 9, 16, 25] <br/>


