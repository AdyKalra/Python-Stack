#### Python was named for the British comedy troupe Monty Python, so why not make our first Python program an homage to their famous Spam skit?

> spam_amount = 0
- Variable assignment! Here we create a variable called spam_amount and assign it the value of 0 using =, Python's assignment operator.

> print(spam_amount)
- A function call. print is an extremely useful builtin Python function that displays the value passed to it on the screen. We call functions by putting parentheses after their name, with the inputs to the function (or arguments) in between.

#### Ordering Spam, egg, Spam, Spam, bacon and Spam (4 more servings of Spam)
> spam_amount = spam_amount + 4
- The first line above is a comment. In Python, comments begin with the # symbol.

> if spam_amount > 0:
> print("But I don't want ANY spam!") 
- The colon (:) at the end of the if line indicates that a new "code block" is coming up. Subsequent lines which are indented (beginning with an extra 4 spaces) are part of that code block. You may be familiar with other languages which use {curly braces} to mark the beginning and end of code blocks. Python's use of meaningful whitespace often is surprising to programmers who are accustomed to other languages, but in practice it can lead to more consistent and readable code than languages that do not enforce indentation of code blocks.
- Strings can be marked either by double or single quotation marks. (But because this particular string contains a single-quote character, we might confuse Python by trying to surround it with single-quotes, unless we're careful.)

- a / b	True division	Quotient of a and b
- a // b	Floor division	Quotient of a and b, removing fractional parts

#### Order of operations
- The arithmetic we learned in primary school has conventions about the order in which operations are evaluated. Some remember these by a mnemonic such as PEMDAS - Parentheses, Exponents, Multiplication/Division, Addition/Subtraction.


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
> squares []
> for x in range (1,11):
> squares.append (x**2)

#### list comprehensions
> squares = [x**2 for x in range (1,11)]

#### slicing a list
> langs = ['python', 'java','R']
> first_two = langs [:2]

#### copying a list
> copy_oflangs = langs[:]


### Tuples
- similar to lists but the items in a tuple cant be modified 
> dimensions = (1920, 1080)

### Dictionaries
- key value pairs
> alien = {'color':'green', 'points':5}
- accessing a value
>print("aliens color" + alien ['Color'])
- adding a key value pair
> alien ['position'] = 5
- looping through all key value pairs 
> for name, point in alien.keys()
> for name, point in alien.items()
> for name, point in alien.values()

#### user input
> name = imput ("org name")

#### functions 
> def models(regression_algo)
> print("algo chosen"+regression_algo)

> models ('bayseian')

### classes
> class model ():
- represents a ML model
> def _init_(self, name):
> self.name = name

> my_model = model ('decisiontree')


### Inheritance
 > class regression(Model)
 represents a regression model
 > def _init_(self,name):
 > super()._init_(name)


### Exceptions
> try:
>  models ("bayesian")
> except ValueError:
> print ("pls try again")
> else:
> print ("model chosen is"+model)


