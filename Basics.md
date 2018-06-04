#### Variables and Strings
- msg = "ady likes learning"
- concatenation +

### Lists
- langs = ['python', 'java']
- langs [0]
- looping through a list
- > for lang in langs:
- > print  (lang)
- lang.append ('R')

#### Numerical lists
- > squares []
- > for x in range (1,11):
- > squares.append (x**2)

#### list comprehensions
- > squares = [x**2 for x in range (1,11)]

#### slicing a list
- > langs = ['python', 'java','R']
- > first_two = langs [:2]

#### copying a list
-  > copy_oflangs = langs[:]


### Tuples
- similar to lists but the items in a tuple cant be modified 
- > dimensions = (1920, 1080)

### Dictionaries
- key value pairs
- >alien = {'color':'green', 'points':5}
- accessing a value
- >print("aliens color" + alien ['Color'])
- adding a key value pair
- >alien ['position'] = 5
- looping through all key value pairs 
- >for name, point in alien.keys()
- >for name, point in alien.items()
- >for name, point in alien.values()

#### user input
- > name = imput ("org name")

#### functions 
- > def models(regression_algo)
- > print("algo chosen"+regression_algo)

- > models ('bayseian')

### classes
- > class model ():
- represents a ML model
- > def _init_(self, name):
- > self.name = name

- > my_model = model ('decisiontree')


### Inheritance
 - > class regression(Model)
 represents a regression model
 - > def _init_(self,name):
 - > super()._init_(name)


### Exceptions
- > try:
- >  models ("bayesian")
- > except ValueError:
- > print ("pls try again")
- > else:
- > print ("model chosen is"+model)


