PRACTICE EXERCISES:
1.Introduction to Variables

2. Collection of Variables

3. Data Types

4. Conditional Statement

5. Loop Statement

6. Functions


1. Introduction to Variables
1.1) What will be the type of the add variable?
a = 10

b = 5.1

add = a + b

a=10
b=5.1
x = a+b
print(x)
15.1

```diff
- Wrong.
```

1.2) Is 5 = (3+2)?
x = (3+2)
print(x)
print(x==5)
## answer
#YES
5
True

```diff
+ Correct!
```

1.3) Add 33 in variable a and print the result
a = 3

a = 3
x=a+33
print(x)
36

```diff
+ Correct!
```

1.4) Convert integer variable a to float and check its type
a = 3

a=3

a= float(a)
print(type(a))
<class 'float'>

```diff
+ Correct!
```

2. Collection of Variables
2.1) Create a list of repeated element (element 2,48 times)
list =[]
list = ["apple","strawberries", "grapes", "watermelon"]
print(list)
['apple', 'strawberries', 'grapes', 'watermelon']

```diff
+ Correct!
```

2.3) Check length of list
List1 =["a","b","c","d","e"]

List1 = ["a","b","c","d","e"]
print("it contains", len(List1), "variables")
it contains 5 variables
2.4) Create a dictionary with the following information:
brand = Audi

Model = Q2

Year = 1980

car= dict["brand":"audi", "model":"Q2", "year":"1980"]
print(car)
dict[slice('brand', 'audi', None), slice('model', 'Q2', None), slice('year', '1980', None)]

```diff
- Wrong.
```

2.5) Create a set of following elements
1.0, "Hello", 55 , (6,7,8)

 ```diff
+ Correct!
```

3. Data Types and String Manipulation
3.1) Printing your name My_Name = "My name is Jupyter!" Also, check if My_Name is all Caps or not. Use isupper() to check returns True if all the letters are Capitals, False if atleast one letter in in lower case.
HINT: My_Name.isupper()

My_Name = "My name is Jupyter"
My_Name.isupper()
False

```diff
+ Correct!
```

3.2) Convert My_Name to all caps. Hint: My_Name.upper().
a = "My_Name"
a.upper()
'MY_NAME'

```diff
- Wrong.
```

3.3) if int1 = "500", what is the Datatype of int1

 

4. Practice Exercise on Conditional Statement
4.1) if x = 20 and y = 30. Write a python code to check if x is less than y.
a = 3
a = float(a)
print(type(a))
<class 'float'>

```diff
- Wrong.
```

4.2) Check if a is equal to 10, If yes, print "Hello", else print "Good Bye"
a = 56

a=56
if a==10:
 print ("Hello")
else: 
 print ("Good Bye")
Good Bye

```diff
+ Correct!
```

4.3) Check whether a number is even or odd
a = 2020

a=2020
if a == %3 :
    print("odd")
else:
    print("even")
  Cell In[157], line 2
    if a == %3 :
            ^
SyntaxError: invalid syntax

```diff
- Wrong.
```

4.4) Check if the word "Data" is present in the sentence "I am a Data Scientist". If found, print "It is present" else print FALSE.
x = "Data"
a = "I am a Data Scientist"
if x is x:
    print ("It is present")
else:

 print ("FALSE")
It is present

```diff
- Wrong.
```

4.5) Write python code to check if a number is positive or negative.


5. Practice Exercise on Loops
5.1) Print Data Science 5 times using for loop
a = "data science"
for loop in range (5):
    print (a)
data science
data science
data science
data science
data science
Note: Remember to keep the index as one more than what is required. In the above code the indexing is done from 0 to 5 which are 6 places but Python has printed it 5 times.

```diff
- Wrong.
```

5.2) Print all the even numbers from 1 to 20 (both inclusive) using for loop.
count = 0
while count < 20:
    count += 1
    if count % 2 == 1:
        continue
    print (count)
2
4
6
8
10
12
14
16
18
20

```diff
+ Correct!
```

6. Function
6.1) Define the python function to check whether the number 33 is even or odd
a = 33
if a % 2:
    print ("odd")

```diff
- Wrong.
```

```diff
! 15/21
```
