# Python-practice-
<body>
print(10>9)
print(10==9)
print(10<9)

a = 200
b= 33

if b>a:
    print("b is greater than a")
else:
    print("b is not greater than a")
</body>


print(bool("hello"))
print(bool(15))
print(bool("&"))

class myclass():
  def __len__(self):
    return 1

myobj = myclass()
print(bool(myobj))

def myFunction() :
  return True

print(myFunction())

def myFunction() :
  return True

if myFunction():
  print("YES!")
else:
   print("No!")


"""
Sure, let’s go through examples of each of the Python assignment operators you’ve asked about:

&= (Bitwise AND assignment operator):
Python

a = 0b101010  # 42 in binary
b = 0b110100  # 52 in binary
a &= b
print(bin(a))  # Output: 0b100000 (32 in binary)
AI-generated code. Review and use carefully. More info on FAQ.
Explanation: The &= operator performs a bitwise AND operation between a and b. Only the bits that are set in both a and b are set in the result.

|= (Bitwise OR assignment operator):
Python

a = 0b101010  # 42 in binary
b = 0b110100  # 52 in binary
a |= b
print(bin(a))  # Output: 0b111110 (62 in binary)
AI-generated code. Review and use carefully. More info on FAQ.
Explanation: The |= operator performs a bitwise OR operation between a and b. The bits that are set in either a or b are set in the result.

^= (Bitwise XOR assignment operator):
Python

a = 0b101010  # 42 in binary
b = 0b110100  # 52 in binary
a ^= b
print(bin(a))  # Output: 0b011110 (30 in binary)
AI-generated code. Review and use carefully. More info on FAQ.
Explanation: The ^= operator performs a bitwise XOR operation between a and b. The bits that are different between a and b are set in the result.

>>= (Right shift assignment operator):
Python

a = 0b101010  # 42 in binary
a >>= 2
print(bin(a))  # Output: 0b1010 (10 in binary)
AI-generated code. Review and use carefully. More info on FAQ.
Explanation: The >>= operator shifts the bits of a to the right by the specified number of positions. In this case, a is shifted right by 2 positions.

<<= (Left shift assignment operator):
Python

a = 0b101010  # 42 in binary
a <<= 2
print(bin(a))  # Output: 0b10101000 (168 in binary)
AI-generated code. Review and use carefully. More info on FAQ.
Explanation: The <<= operator shifts the bits of a to the left by the specified number of positions. In this case, a is shifted left by 2 positions.

These operators are useful for manipulating individual bits of data, which can be particularly handy in low-level programming or when dealing with binary data"""

# in above code you need to first convert the number in the binary format then you able to do perform the operation in it  :

"""n Python, the expression print(4 or 5 + 10 or 8) involves the use of the or logical operator. The or operator returns the first truthy value among its operands or the last operand if none are truthy. In Python, non-zero numbers are considered truthy, and zero is considered falsy.

Here’s how the expression is evaluated:

Python evaluates the expression from left to right.
4 or 5 + 10 is evaluated first. Since 4 is a non-zero number, it is truthy, so Python doesn’t even evaluate 5 + 10. It returns 4 immediately.
Now, the expression is effectively 4 or 8. Again, since 4 is truthy, Python returns 4 without evaluating 8.
So, the final output of the expression print(4 or 5 + 10 or 8) is 4."""

thislist = ["apple", "banana", "cherry"]
print(thislist)

thislist = list(["apple", "banana", "cherry"])
print(type(thislist))

thislist = ["apple", "banana", "cherry"]
thislist.insert(2, "watermelon")
print(thislist)

thislist = ["apple", "banana", "cherry"]
for x in thislist:
  print(x)


thislist = ['radha', 'krishna', 'riya']
i = 0
while i < len(thislist):
   print(thislist[i])
   i = i + 1
   
newlist = [x for x in range(10) if x < 5]
print(newlist)

fruits = ["apple", "banana", "cherry", "kiwi", "mango"]

newlist = [x.upper() for x in fruits]

print(newlist)

# it convert all the strings in the list in upper case
fruits = ["apple", "banana", "cherry", "kiwi", "mango"]

newlist = ['hello' for x in fruits]

print(newlist)



fruits = ["apple", "banana", "orange", "kiwi", "mango"]

newlist = [x if x != "banana" else "orange" for x in fruits]

print(newlist)

x = [1,2,3]
y = [4,5,6]
z = [x,y]
print(z[0][1])

def myfunc(n):
  return abs(n - 50)

thislist = [100, 50, 65, 82, 23]
thislist.sort(key = myfunc)
print(thislist)


# list []
# tuple ()
# set {}
#  dictionary {a:b}

thistuple = ('apple', 'banana', 'cherry')
print(len(thistuple))

radha = ("krishna",)
print(type(radha))

radha = ("krishna")
print(type(radha))

miya = [ 'rohan', 'saloni', 'max']
print(type(miya))


# you can access any tuple, list etc like this instead you can access negative numbers too 
game = ('ganga', ' gun', 'shoot')
print(game[1])

tekken_7 = ['kill', ' fight', 'die']
print(tekken_7[0])

AI = ('love', 'tech', 'skilled', '2025', 'microsoft', 'japan', 'outside India')
print(AI[2:5])

thistuple = ("apple", "banana", "cherry")
if "apple" in thistuple:
  print("Yes, 'apple' is in the fruits tuple")

''' Once a tuple is created, you cannot change its values. Tuples are unchangeable, or immutable as it also is called.

But there is a workaround. You can convert the tuple into a list, change the list, and convert the list back into a tuple.'''

x = ("apple", "banana", "cherry")
y = list(x)
y[1] = "kiwi"
x = tuple(y)

print(x)


monica = ('my darling', 'ghost', 'cutie')
y = list(monica)
y.append('evil')
monica = tuple(y)
print(monica)

# you can delete the tuple direclty you don't need to convert it into list
# because delete keyword delete the whole tuple that's why 


fruits = ('apple', 'banana', 'cherry', 'ghost')

(sexy, *horny, red) = fruits

print(sexy)
print(horny)
print(red)

# in which string you use asterisk then a list will made from there 
# and moving from forward everything is going on in unpack format

kudamono = ('apple', 'banana', 'cherry', 'ghost')
(red, green, *yellow) = kudamono
print(red, green, yellow)

thistuple = ('cat', 'inu', 'ohayo')
for x in thistuple:
   print(x)

ghost = (34, 23, 56)
mytuple = ghost * 2
print(mytuple)

thistuple = ( 24, 23, 11, 32)
 
x = thistuple.index(23)

print(x)


# the values True and 1 are considered the same value in sets, and they are treated as duplicates
# and same like True and 1 both False and 0 are treated in the same way too :)
mother = {'evil', 'anger', 'bad mouth', True, 1, 2, False, 0 }
print(mother)

thisset = {'cat', 'dog', 'mouse'}
print('banana' in thisset)

thisset = {'cat', 'dog', 'mouse'}
print('banana' not in thisset)

lame = {"class", 'lecture', 'teacher'}

lame.add('orange')
print(lame)

daddy = {'papa', 'father','soft'}
mummy = {'mummy', 'mother', 'volcano'}

daddy.update(mummy)
print(daddy)

thisset = {"apple", "banana", "cherry"}

thisset.clear()

print(thisset)


# you can use for loop (only) in the set

vikram = {'suhani', 'sunanna', 'ragini'}

for x in vikram:
   print(x)

set1 = {"a", "b", "c", 3}
set2 = {1, 2, 3}
set3 = {"John", "Elena"}
set4 = {"apple", "bananas", "cherry"}

myset = set1.union(set2, set3, set4)
print(myset)

x = {"a", "b", "c"}
y = (1, 2, 3)

z = x.union(y)
print(z)


thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
print(thisdict)

thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
x = thisdict["model"]
print(x)


lalaji = { 
   "mota": "peet",
   "rasgule": "halwai",
   "jalebi": "milk"
}
gochu = lalaji.get("jalebi")
print(gochu)

lalaji = { 
   "mota": "peet",
   "rasgule": "halwai",
   "jalebi": "milk"
}
baby = lalaji.keys()
print(baby)

lalaji['middle'] = 'class'

print(baby)
print(lalaji)


ritika = {
   'university':'student',
   'friend': 'ghost',
   'trees':'grandfather',
   }
x = ritika.values()
print(x)

ritika['granny'] = 'amar'
print(x)
print(ritika)


krishna = {
   'brother': 'younger',
   'god': 'satyug',
   'mahabharata': 'arjun'
}
pandav = krishna.items()
print(pandav)

krishna['draupdi'] = "arjun_wife"
print(pandav)
print(krishna)


krishna = {
   'brother': 'younger',
   'god': 'satyug',
   'mahabharata': 'arjun'
}
if "god" in krishna:
   print("yes, krishna is the god")
# Output: yes, krishna is the god

# you can change the value of a specific item by referring to its key name
 
google = {
    'internship': ' winter',
    'november': 'SDE',
    'year': 2024
 }

google['year'] = 'same'
print(google) # you can also change the value by update() method too.

google = {
    'internship': ' winter',
    'november': 'SDE',
    'year': 2024
 }
google.update({'year':'same'})
print(google)

# you can also add dictionary direct and with the help of update() by using new keys:values
# you can use pop() method to remove the items just use keys and it will remove that keys:values in the dictionary
# but popitem() removes only the last keys:values in the dictionary
# you can use del keyword to delete the item in the dictionary just by giving the keys but you can also delete the  whole dictionary without passing the keys in the dictionary
# you can use clear() method just to empty the dictionary


'''you  can loop through a dictionary by using a for loop
where only items() method will display the dictionary in keys:values format'''

devin = {
   "AI": "Robot",
   "Tech": "ML",
   "Skill": "Challenge"
}
for x, y in devin.items():
   print(x, y)

''' to get only the keys names in the dictionary through loop
wise we have two methods -direct and another -keys()'''

# Method 1
devin = {
   "AI": "Robot",
   "Tech": "ML",
   "Skill": "Challenge"
}

for x in devin:
   print(x)

# Method 2
devin = {
   "AI": "Robot",
   "Tech": "ML",
   "Skill": "Challenge"
}

for x in devin.keys():
   print(x)

''' to get only the values names in the dictionary through 
loop we have two methods, -direct but write name_of_dictionary[x] 
in the print statement and another by using -values() method'''

# Method 1 
devin = {
   "AI": "Robot",
   "Tech": "ML",
   "Skill": "Challenge"
}

for x in devin:
   print(devin[x])

# Method 2

devin = {
   "AI": "Robot",
   "Tech": "ML",
   "Skill": "Challenge"
}

for x in devin.values():
   print(x)


""" There are only two ways to make a copy in the dictionary
one is by the help of copy() method and another is by the help
of dict() function"""

# Built-in Dictionary method = copy()
Radhika = {
   'lucky': 'racer',
   'mohini': 'Apsara',
   'Devika': 'Friend'
}
mydict = Radhika.copy()
print(mydict)

# Built-in Function = dict()
Radhika = {
   'lucky': 'racer',
   'mohini': 'Apsara',
   'Devika': 'Friend'
}
mydict = dict(Radhika)
print(mydict)

''' A dictionary can contain dictionaries, this is called 
nested dictionaries'''

# you can create a dictionary that contain three dictionaries in it and many more

myfamily = {
   "elder_child" : {
      "name": "ishu",
      "year": 2004
   },
   "middle_child" :{
      "name": "gappu",
      "year": 2005
   },
   "junior_child": {
      "name": "krishna",
      "year": 2012
   }
}
print(myfamily)

# by making three dictionaries then add it to the one(main) dictionary, you can also do that

elder_child = {
    "name": "mohini",
    "year": 1927
}
middle_child = {
   "name": "rohit",
   "year": 2001
}
junior_child = {
   "name": "suzuka",
   "year": 2000
}

myfamily = { 
   "elder_child" : elder_child,
   "middle_child" : middle_child,
   "junior_child" : junior_child
}

print(myfamily)


# Access items in the nested dictionaries

elder_child = {
    "name": "mohini",
    "year": 1927
}
middle_child = {
   "name": "rohit",
   "year": 2001
}
junior_child = {
   "name": "suzuka",
   "year": 2000
}

myfamily = { 
   "elder_child" : elder_child,
   "middle_child" : middle_child,
   "junior_child" : junior_child
}

print(myfamily["middle_child"]["name"])



''' loop through nested dictionaries'''


#  But his approach only give you the whole name of the last dictionary only (remember that)
# that,s why it is not much useful approach
elder_child = {
    "name": "mohini",
    "year": 1927
}
middle_child = {
   "name": "rohit",
   "year": 2001
}
junior_child = {
   "name": "suzuka",
   "year": 2000
}

myfamily = { 
   "elder_child" : elder_child,
   "middle_child" : middle_child,
   "junior_child" : junior_child
}

for x, obj in myfamily.items():
   print(x) # we use x because x display keys

for y in obj:
   print(y + ':', obj[y]) 
   """ we use y + to add ':' in the code
   because the code will never display it and always hide it but
   by adding  like that it will display in the terminal and + icon works 
   to add it , that's why we write again obj[y] because to display it again
   in the print format too and then run"""



# another example (this is the best approach)

myfamily = {
   "elder_child" : {
      "name": "ishu",
      "year": 2004
   },
   "middle_child" :{
      "name": "gappu",
      "year": 2005
   },
   "junior_child": {
      "name": "krishna",
      "year": 2012
   }
}
print(myfamily)

for x, obj in myfamily.items():
   print(x)

   for y in obj:
      print(y + ':', obj[y])




# Another way

# Create a list of dictionaries
children = [
    {
        "role": "elder_child",
        "name": "mohini",
        "year": 1927
    },
    {
        "role": "middle_child",
        "name": "rohit",
        "year": 2001
    },
    {
        "role": "junior_child",
        "name": "suzuka",
        "year": 2000
    }
]

# Loop through the list of dictionaries
for child in children:
    print(child["role"])  # Print the role of the child
    print("Name:", child["name"])  # Print the name of the child
    print("Year:", child["year"])  # Print the birth year of the child
    print()  # Add an empty line for readability


# setdefault() returns the value if exist if not then by default it will display given value

car = {
   'brand': 'lambogiri',
   'model': 'titan',
   'year': 2009
}

x = car.setdefault('model', 'tiger')
print(x)



car = {
   'brand': 'lambogiri',
   'model': 'titan',
   'year': 2009
}
x = car.setdefault('color', 'black')
print(x)



# fromkeys method display the value if present if not then it will display none as an value of the keys

x = ("key1", "key2", "key3")
y = 0
thisdict = dict.fromkeys(x, y)
print(thisdict)

x = ("key1", "key2", "key3")
thisdict = dict.fromkeys(x)
print(thisdict)


# get() method will give us the value by passing the keys and if that doesn't exist then it will give us the given value

# example 1
car = {
   'brand': 'ford',
   'model': 'mustang',
   'year': 1964
}
x = car.get("model")
print(x)

# example 2
car = { 
   'brand': 'ford',
   'model': 'mustang',
   'year': 1964
}
x = car.get('price', 15000)
print(x)

""" we use conditional statement where we use if , elif and else
statement if (if statement doesn't work then we use elif statement
and if elif doesn't work then we use else which catches
anything which isn't caught by the preceding conditions.)"""

a = 200
b = 33
if b > a:
   print("b is greater than a")
elif a == b:
   print("a and b are equal")
else:
   print("a is greater than b")


a = 200
b = 33
c = 500
if a > b and c < a:
   print("yes")
else:
   print("No")


# nested if = you can have if statements inside if statements, this is called nested if statement.

x = 41 
if x > 10:
   print("above ten,")
   if x > 20:
      print("and also above 20!")
   else:
      print("but not above 20.")

""" pass statement = if statements cannot be empty, but if you for 
some reason have an if statement with no content, and you don't want 
to display it in your code than put the pass statement at the of 
your code to avoid getting an error. """

a = 33
b = 200

if b > a:
   pass


""" python has two primitive loop  commands:-
     1.   while loops
     2.   for loops"""

# while loop = we can execute a set of statements as long as a condition is true.

i = 1
while i < 6:
   print(i)
   i += 1



# continue statement = we can stop the current iteration and continue with the next
i = 1
while i < 6:
   i +=1
   if i == 3:
      continue
   print(i)


# break statement = we can stop the loop even if the while condition is true (infinite loop)
i = 1 
while i < 6:
   print(i)
   if i == 3:
      break
   i += 1

   
# else statement = we can run a block of code once when the condition no longer is true.
i = 1
while i < 6:
   print(i)
   i += 1
else:
   print("i is no longer less than 6")



""" A for loop is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set or a string)"""

fruits = ['apple', 'banana', 'cherry']
for x in fruits:
   print(x)

# it also work on a single string too remember that
for x in 'banana':
   print(x)

# you can use break statement in the loop in two ways but you can use it in that way in while loop instead it will become a forever loop(infinite).

# Method 1 
fruits = ['apple', 'banana', 'cherry']
for x in fruits:
   print(x)
   if x == 'banana':
      break

# Method 2
fruits = ['apple', 'banana', 'cherry']
for x in fruits:
   if x == 'banana':
      break
   print(x)

# we use continue statement to stop the current iteration of the loop 

fruits = ['apple', 'banana', 'cherry']
for x in fruits:
   if x == 'banana':
      continue
   print(x)


# we can use else to specifies a block of code to be executed when the loop is finished

for x in range(6):
   if x == 3: break
   print(x)
else:
   print('finally finished!')


# we have nested loops to inside a loop 

adj = ['red', 'big', 'tasty']
fruits = ['apple', 'banana', 'cherry']
for x in adj:
   for y in fruits:
      print(x, y)


""" Now it is time to start the function in the python my sweety"""

def my_function():
   print("Hello  from a function")
my_function()


def my_function(fnames):
   print(fnames + '  Refsnes')

my_function('radhika')
my_function('gauri')
my_function('sunanah')


def my_function(fname, lname):
   print(fname + " " + lname) # remember here " " is a space which make for the space or gape between the sentences

my_function('Adrika', 'Panwar')



# if you don't know how many arguments that will be passed into your function then add a * before the parameter name in the function definition
def my_function(*kids):
   print("the youngest child is " + kids[1])

my_function("Rohini", "Nitarika", "Simi")


# you can also send arguments with the key = value syntax (order doesn't matter here)
def my_function(child3, child2, child1):
  print("The youngest child is " + child3)

my_function(child1 = "Emil", child2 = "Tobias", child3 = "Linus")


""" Simple Aruguments = *    
    Keyword Arguments = **     """

def my_function(**kid):
  print("His last name is " + kid["lname"])

my_function(fname = "Tobias", lname = "Refsnes")


# default parameter in function 
def my_function(country = "Norway"):
   print("I am from " + country)

my_function("Sweden")
my_function("India")
my_function()
my_function("Brazil")



"""you can send any data types of arguments to a function(string, number, list, dictionary etc),
and it will be treated as the same data type inside the function. """
def my_function(food):
  for x in food:
    print(x)

fruits = ["apple", "banana", "cherry"]

my_function(fruits)



def my_function(x):
  return 5 * x

print(my_function(3))
print(my_function(5))
print(my_function(9))


# In positional arguments order matters , / add it after the arguments
def my_function(x, /):
   print(x)

my_function(3)

# you are allowed to use positional arguments if the function expects keyword arguments by simply write it
def my_function(x):
   print(x)

my_function(3)

# In keyword arguments order doesn't matter  *, add it before the arguments
def my_function(*, x):
   print(x)

my_function(x = 3)

# you are allowed to use keyword arguments if the function expects positional arguments by simply write it
def my_function(x):
   print(x)

my_function(x = 3)


# you can combine the two argument types in the same function
def my_function(a, b, /, *, c, d): # notice there , / and *, you use here and see the call function too you can understand it easily
   print(a + b + c + d)

my_function(5, 6, c = 7, d = 8)



""" Recursion is a common mathematical and programming concept. 
It  means that a fucntion calls itself. This has the benfit of 
meaning that you can loop through data to reach a result. """

# tri_recursion() is a function that we have defined to call itself("recurse")

def tri_recursion(k):
   if(k > 0):
      result = k + tri_recursion(k - 1)
      print(result) # here we add starting from 1 and continue till 6 times
   else: # see there:- 1, 1+2 = 3, 3+3 = 6, 6+4 = 10 etc now notice it very well then you understand how it proceed
      result = 0  # if you are thing that what about k - 1 than think again than you notice that it already subtracted think logically baby!
   return result

print("\n\nRecursion Example Results")
tri_recursion(6)



# you can use pass statement to avoid the error
def myfunction():
   pass


""" lambda function is used as a anonmymouly but it work as a short cut means
you can put many as you want arguments but it generate only one expression
and expresssion just make it to process but result comes out later
it is used mostly in map, filter and reduce type places etc and GUI libraries
too like Tkinter and PyQt"""

x = lambda a, b : a * b
print(x(5, 6))

x = lambda a : a + 10
print(x(5))


# The power of lambda is better shown when you use them as an anonymous function inside another function
def myfunc(n):
  return lambda a : a * n

mydoubler = myfunc(2)

print(mydoubler(11))


def myfunc(n):
  return lambda a : a * n

mydoubler = myfunc(2)
mytripler = myfunc(3)

print(mydoubler(11))
print(mytripler(11))


# An Array is a special variable, which can hold more than one value at a time.

cars = ["Ford", "Volvo", "BMW"]

cars[0] = "Toyota"

print(cars)



fruits = ['apple', 'banana', 'cherry']

fruits.insert(1, "orange")

print(fruits)

""" python is an object oriented programming langauge, python is an object,
with its properties and methods
A class = object constructor = blueprint """

class MyClass: # to create a class, use the keyword class
  x = 10

print(MyClass)


# now we can use the class named MyClass to create objects
class MyClass:
  x = 10

menakshi = MyClass()
print(menakshi.x)


# ye apna desi jadu( but remember these simpliest form are not useful in the real life applications)
class rohini:
   riya = 25

nishant = rohini()
print(nishant.riya)

""" 1.  To understand the meaning of classes we have to understand the built- in _init_() function .
    2.  All classes have a function calles _init_(), which is always executed when the class is being initiated.
    3.  Use the _init_() function to assign values to object properties, or other operations that are necessary to do when the object is being created. """



class student:
  def __init__(stu, name, age):
    stu.name = name
    stu.age = age

p1 = student("John", 36)

print(p1.name)
print(p1.age)

# The __init__() function is called automatically every time the class is being used to create a new object.
class student:
   def __init__(stu, name, age): # you got the error again and again because you are using _init_ but remember you have to use __init__ means double dash rather than single
      stu.name = name
      stu.age = age

p1 = student("John", 19)

print(p1.name)
print(p1.age)

''' rather than writing print(p1. name), print(p1.age)
   much more you can use __str__() function to write it whole in one line but convert
   the integer (number) etc in the string see how it is helpful
   '''

# code directly working without the __str__() function:-
class Person:
  def __init__(self, name, age):
    self.name = name
    self.age = age

p1 = Person("John", 36)

print(p1)

# code run with __str__() function
class Person:
  def __init__(self, name, age):
    self.name = name
    self.age = age

  def __str__(self):
    return f"{self.name}({self.age})" # f "" denotes here formatting string 

p1 = Person("John", 36)

print(p1)

# objects can also contain methods. methods in objects are functions that belong to the object
class employee:
   def __init__(stu, name, age):
      stu.name = name
      stu.age = age

   def myfunc(stu):
      print("Hi my name is " + stu.name)

p1 = employee("Rohan", 24)
p1.myfunc()

# notice abc here to then you understand that at def myfunc() you can put any name in the bracket
class Person:
  def __init__(mysillyobject, name, age):
    mysillyobject.name = name
    mysillyobject.age = age

  def myfunc(abc):
    print("Hello my name is " + abc.name)

p1 = Person("John", 36)
p1.myfunc()

# you can modify the object properties like that:-
class Person:
  def __init__(self, name, age):
    self.name = name
    self.age = age

  def myfunc(self):
    print("Hello my name is " + self.name)

p1 = Person("John", 36)

p1.age = 40 # you can do the same way to just for delete the object age but it will delete the whole age line which give you as output that this attribute doesn't exist (use (del p1.age)) to delete 
# you can use (del p1) but it delete whole p1 line and again error show
print(p1.age)


class student:
  pass


# we create a parent class here
class minu:
   def __init__(self, fname, lname):
      self.firstname = fname
      self.lastname = lname

   def printrohan(self):
      print(self.firstname, self.lastname)

x = minu("Adrika", "Panwar")
x.printrohan()



class Person:
  def __init__(self, fname, lname):
    self.firstname = fname
    self.lastname = lname

  def printname(self):
    print(self.firstname, self.lastname)

class Student(Person): # you can't remove it because if you do so then whole code when you run then it give error because you doesn't describe student here but if you leave it it will show it as a define way
  pass # but instead of pass you can also add some changes here to just like up by writing __init__() etc etc

x = Student("Mike", "Olsen")
x.printname()

""" But When you add the __init__() function, the child class will no longer inherit the parent's __init__() function.
    The child's __init__() function overrides the inheritance of the parent's __init__() function.
   To keep the inheritance of the parent's __init__() function, add a call to the parent's __init__() function:
       """
class Person:
  def __init__(self, fname, lname):
    self.firstname = fname
    self.lastname = lname

  def printname(self):
    print(self.firstname, self.lastname)

class Student(Person):
  def __init__(self, fname, lname):
    Person.__init__(self, fname, lname) #  you know naa! why we add it here
 # you cannot add anything here but you can add it in supper()
x = Student("Mike", "Olsen")
x.printname()

"""Python also has a super() function that will make the child class inherit all the methods and properties from its parent:
   By using the super() function, you do not have to use the name of the parent element, it will automatically inherit the methods and properties from its parent.
   you cannot add anything in directly call to the parent,s in __init__() (see the above code)
    but you can add anything in super()"""

class Person:
  def __init__(self, fname, lname):
    self.firstname = fname
    self.lastname = lname

  def printname(self):
    print(self.firstname, self.lastname)

class Student(Person):
  def __init__(self, fname, lname):
    super().__init__(fname, lname)

x = Student("Mike", "Olsen")
x.printname()


# Adding in supper()
class Person:
  def __init__(self, fname, lname):
    self.firstname = fname
    self.lastname = lname

  def printname(self):
    print(self.firstname, self.lastname)

class Student(Person):
  def __init__(self, fname, lname):
    super().__init__(fname, lname)
    self.graduationyear = 2019

x = Student("Mike", "Olsen")
print(x.graduationyear)
x.printname()

#  both give the same output
class Person:
  def __init__(self, fname, lname):
    self.firstname = fname
    self.lastname = lname

  def printname(self):
    print(self.firstname, self.lastname)

class Student(Person):
  def __init__(self, fname, lname, year):
    super().__init__(fname, lname)
    self.graduationyear = year # chahe 2019 yaha likho

x = Student("Mike", "Olsen", 2019) # ya yaha likho output same ana hai
print(x.graduationyear)
x.printname()

# Don't add same name or method or anything in the child classs with the parent class function instead it will overridden.

class Person:
  def __init__(self, fname, lname):
    self.firstname = fname
    self.lastname = lname

  def printname(self):
    print(self.firstname, self.lastname)

class Student(Person):
  def __init__(self, fname, lname, year):
    super().__init__(fname, lname)
    self.graduationyear = year

  def welcome(self): # you can do this tooo by adding more and more
    print("Welcome", self.firstname, self.lastname, "to the class of", self.graduationyear)

x = Student("Mike", "Olsen", 2019)
x.welcome()

""" Iterators = repeating a process; An iterator is an object that contains a countable no. of values.
     It is an object that can be iterated upon, meaning that you can traverse through all the values.
     Technically, in python, It is an object which implements the iterator protocol, which consist of the 
     methods __iter__()  and  __next__()"""


# lists, tuples, dictionaries, and sets are all iterable objects and also even strings too can return an iterator.
# All these objects have a iter() method which is used to get an iterator.

mytuple = ("apple", "banana", "cherry")
myit = iter(mytuple)

print(next(myit))
print(next(myit))
print(next(myit))


mystr = "banana"
myit = iter(mystr)

print(next(myit))
print(next(myit))
print(next(myit))
print(next(myit))
print(next(myit))
print(next(myit))

# we can also use a for loop to iterate through an iterable object.
mytuple = ("apple", "banana", "cherry")

for x in mytuple:
   print(x)

""" To create an object/class as an iterator you have to implement the methods __iter__() and __next__() to your object.
     as __init__() allows you to do some intializing when the object is being created 
      In the same way __iter__() acts, you can do operations(initializing etc.), but must always return the iterator 
      object itself.
      The __next__() method also allows you to do operations, and must return the next item in the sequence."""

# we can use __iter__() and __next__() in numbers mostly 
class MyNumbers:
  def __iter__(self):
    self.a = 1
    return self

  def __next__(self):
    x = self.a
    self.a += 1
    return x

myclass = MyNumbers()
myiter = iter(myclass)

print(next(myiter)) # but in this you have to type print again and again and you don't know where to stop; so it work as a inifinity
print(next(myiter))
print(next(myiter))
print(next(myiter))
print(next(myiter))

# to prevent the continue forever and the iteration from going on forever, we can use the stopIteration statement

class MyNumbers:
  def __iter__(self):
    self.a = 1
    return self

  def __next__(self):
    if self.a <= 20:
      x = self.a
      self.a += 1
      return x
    else:
      raise StopIteration

myclass = MyNumbers() # remember we have to use it because it help to run the function 
myiter = iter(myclass) # same here this too 

for x in myiter:
  print(x)


""" polymorphism means using a same function and class in diffrenet way
and then use it in a same way like we can use len() function in strings, dict and tuples 
in different way and now here we work on class now see the example below!"""

class Car:
  def __init__(self, brand, model):
    self.brand = brand
    self.model = model

  def move(self):
    print("Drive!")

class Boat:
  def __init__(self, brand, model):
    self.brand = brand
    self.model = model

  def move(self):
    print("Sail!")

class Plane:
  def __init__(self, brand, model):
    self.brand = brand
    self.model = model

  def move(self):
    print("Fly!")

car1 = Car("Ford", "Mustang")       # Car class
boat1 = Boat("Ibiza", "Touring 20") # Boat class
plane1 = Plane("Boeing", "747")     # Plane class

for x in (car1, boat1, plane1):
  x.move() # now at the end, because of polymorphism we can execute the same method for all three classes


# Another Method:-
class Vehicle:
  def __init__(self, brand, model):
    self.brand = brand
    self.model = model

  def move(self):
    print("Move!")

class Car(Vehicle):
  pass

class Boat(Vehicle):
  def move(self):
    print("Sail!")

class Plane(Vehicle):
  def move(self):
    print("Fly!")

car1 = Car("Ford", "Mustang") #Create a Car object
boat1 = Boat("Ibiza", "Touring 20") #Create a Boat object
plane1 = Plane("Boeing", "747") #Create a Plane object

for x in (car1, boat1, plane1):
  print(x.brand)
  print(x.model)
  x.move()


def tornto():
  azax = "siet"
  def uni():
    nonlocal azax
    azax = " atama i`"
  uni()
  return azax
print(tornto())


import platform # it is a built-in modules means it is already comes with python you don't need to pip install it
  
x = platform.system()
print(x)

x = dir(platform)
print(x)

import datetime
x = datetime.datetime.now() # date contains year, month, day, hour, minute, second, and microsecond.
print(x)

x = datetime.datetime.now()
print(x.year)
print(x.strftime("%A")) # strftime display the date object into readable strings and "%A" represents weekday

# datetime() constructor define year, month, day. but it also define hour, min, sec, microsec, tzone but as a optional rather than it set it as a default 00.00.00.000000
import datetime

x = datetime.datetime(2020, 5, 17)

print(x)

# strftime() method formats date objects into readable strings.
import datetime

x = datetime.datetime(2018, 6, 1)

print(x.strftime("%B")) # "%B" used for month


# hahahaha neeche jo ab code hai vo sirf % yani pattern kahu to dhikane ko hai datetime() ka
import datetime

x = datetime.datetime.now()

print(x.strftime("%%"))


# the pow(x, y) returns the value of x to the power of y(x^y))
x = pow(4, 5)
print(x)

# abs() function give the negative number into a positive number
x = abs(-7.25)
print(x)


import math
x = math.sqrt(64)
print(x)


# math.ceil() rounds a no. upwards to its nearest integer
# math.floow() rounds a no. downwards to its nearest integer

x = math.ceil(1.4)
y = math.floor(1.4)

print(x) 
print(y) 

x = math.pi # it gives pi value
print(x)

# JSON is a syntax for storing and exchanging data , it is text, written with javascript object notation.
# python has a built-in package called json, which can be used to work with JSON data.

import json
# some JSON:
x =  '{ "name":"John", "age":30, "city":"New York"}'

# parse x:
y = json.loads(x) # json.loads convert the json string to python dictionary

# the result is a Python dictionary:
print(y["age"])



# now you can convert python to json but python needs to be in dictionary form , you can covert through json.dumps()
# a Python object (dict):
x = {
  "name": "John",
  "age": 30,
  "city": "New York"
}

# convert into JSON:
y = json.dumps(x)

# the result is a JSON string:
print(y)


# it is not easy to read the json without indentations and line breaks it becomes tough so we put indentation with json.dumps(x, indent=4) which indent and make easy to read the code
x = {
  "name": "John",
  "age": 30,
  "married": True,
  "divorced": False,
  "children": ("Ann","Billy"),
  "pets": None,
  "cars": [
    {"model": "BMW 230", "mpg": 27.5},
    {"model": "Ford Edge", "mpg": 24.1}
  ]
}

# use four indents to make it easier to read the result:
print(json.dumps(x, indent=4))# here we use indent parameter to put the indentations remember that


# we can also use separator parameter to make the indentation much easier
x = {
  "name": "John",
  "age": 30,
  "married": True,
  "divorced": False,
  "children": ("Ann","Billy"),
  "pets": None,
  "cars": [
    {"model": "BMW 230", "mpg": 27.5},
    {"model": "Ford Edge", "mpg": 24.1}
  ]
}

# use . and a space to separate objects, and a space, a = and a space to separate keys from their values:
print(json.dumps(x, indent=4, separators=(". ", " = ")))


# to sort json in alphabetical order
x = {
  "name": "John",
  "age": 30,
  "married": True,
  "divorced": False,
  "children": ("Ann","Billy"),
  "pets": None,
  "cars": [
    {"model": "BMW 230", "mpg": 27.5},
    {"model": "Ford Edge", "mpg": 24.1}
  ]
}
print(json.dumps(x, indent=4, sort_keys=True))



""" RegEx = regular Expression, is a sequence of characters that 
    forms a search pattern.
    It can be used to check if a string contains the specified search pattern."""

import re

txt = "The rain in Spain"
x = re.search("^The.*Spain$", txt) # it search the string starts with "The" and ends with "Spain"
if x:
  print("YES! We have a match!")
else:
  print("No match")


# \ this icon is used for the special character , you can put any character behind it but not any only specific one which is useful and suitable
# which is given by the regression expression by ownself.

""" if you want to get the metacharacters, special sequence character and sets characters than go through the notebook firsts
now here i am only describing about  RegEx expression. """

# findall() function returna a list containing given matches.
import re # you have to first import the libraray whether you have to pip install it or wheteher it is built-in 

txt = "The rain in Spain"
x = re.findall("ai", txt)
print(x)

# search() function searches the string for a match, and returns a match object if there is a match
# if there is more than one match, only the first occurrence of the match will be returned

txt = "The rain in Spain"
x = re.search("\s", txt)

print("The first white-space character is located in position:", 
x.start())



txt = "The rain in Spain"
x = re.search("Portugal", txt)
print(x) # if not present then the none will be displayed like in findall [] this will display as none here none is displayed


# split() function returns a list where the string has been split at each match means at the white-space too
txt = "The rain in Spain"
x = re.split("\s", txt)
print(x)

txt = "The rain in Spain"
x = re.split("\s", txt, 1) # you can control the number of occurrences by specifying the maxsplit parameter here 1 is the one split command maxsplit parameter as many number you give it will work on it as like it
print(x)




# sub() function replaces the matches with the text of your choice
txt = "The rain in Spain"
x = re.sub("\s", "9", txt)
print(x)


txt = "The rain in Spain"
x = re.sub("\s", "9", txt, 2)# you can control the number of replacements by specifying the count parameter by replace the give choice of you character/number in how many count you have given to the command
print(x)


""" In python, search() function is a match object; The Match object has properties and methods used to retrieve information about the search and the result.
   1.  .span() returns a tuple containing the start-, and end positions(index) of the match only
   2.  .string() returns the string passed into the function, means give us the whole string means given string
   3.  .group() returns the part of the string where there was a match """

txt = "The rain in Spain"
x = re.search(r"\bS\w+", txt)
print(x.span())

txt = "The rain in Spain"
x = re.search(r"\bS\w+", txt)
print(x.string)

txt = "The rain in Spain"
x = re.search(r"\bS\w+", txt)
print(x.group())



from playsound import playsound
# Title: "Dreamy Serenade"
# Key: C Major

# Melody
melody = [
    ("C4", 0.5), ("D4", 0.5), ("E4", 0.5), ("F4", 0.5),
    ("G4", 0.5), ("A4", 0.5), ("B4", 0.5), ("C5", 0.5),
    ("B4", 0.5), ("A4", 0.5), ("G4", 0.5), ("F4", 0.5),
    ("E4", 0.5), ("D4", 0.5), ("C4", 0.5), ("C4", 0.5),
]

# Chords
chords = [
    ("C4", ["C4", "E4", "G4"]),  # C Major
    ("F4", ["F4", "A4", "C5"]),  # F Major
    ("G4", ["G4", "B4", "D5"]),  # G Major
    ("C4", ["C4", "E4", "G4"]),  # C Major
]

# Create the music
music = []
for note, duration in melody:
    music.append(note)
    music.extend(chords)

# Play the music (imagine a beautiful piano)
for note in music:
    print(f"Playing {note}...")

print("🎶 Dreamy serenade complete! 🎶")
