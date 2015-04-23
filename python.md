# Python Primer
The purpose of this book is to give the reader a basic understanding of Python. Written by [Andor  Salga](https://asalga.wordpress.com).

## Starting Out
To begin working with Python, go to the [official site](https://www.python.org/) and navigate to the download section. Download and install the Python interpreter. You can use this to begin coding. Alternatively, you can learn using an online resource, such as [CodeCademy](http://www.codecademy.com/tracks/python)

## The Basics
Some things to keep in mind before starting your Python development:

 * Python is **not** free-form; indentation and whitespace has contextual significance
 * Python is case-sensitive


## Output
The first thing you need to know is how to write to the console. We do this by using **print**.

    print 'Hello, single quotations!'
    print "Hello double quotations!!"
    print """Hello TRIPLE quotations!!!"""


## Data Types
Python has five built-in data types:

* Number
* String
* List
* Tuple
* Dictionary

## Variables
To create a variable, simply assign a value to a label:

    number = 3.14
    string = 'A snake came to my water-trough...'
    list = [2,3,5,7,11];
    tuple = ('pi', 3.14159)
    dictionary = {'python', 'A large nonvenomous constrictor snake'}

## Control Flow
We can control the flow of our script with conditionals and loops.

### Conditionals
We use the **if**, **elif** and **else** keywords to control the flow of our script.

    if(True):
        print 'This will be printed'
    
    if(0 == 1):
        print 'This will NOT be printed'
    elif(True == False):
        print 'This will also not be printed.'
    else:
        print 'This will be printed'
    

#### Loops
Similar to other languages, Python has two constructs for loops: **for** and **while**.

#### while
While loops

#### for
    for i in range(1,3):
        print i
    # result:
    # 1
    # 2
    
## Common String Operations
    'make me uppercase'.upper()
    'MAKE ME LOWER!'.lower()

## Math Expressions
Python has a built-in method of raising numbers to an exponent.

    twoFiftySix = 2**8;
    
## Functions
We can define a function with the **def** keyword. Note, you must indent all the code you want to be part of the funciton body.

    def function():
        return 42

## Classes


## Keyword Reference
Here is a alphabetized list of Python's keywords:
<!---
| and | as | assert | break | class | continue | def |
| -- | -- | -- | -- | -- | -- | -- |
| del | elif | else | except | 4:2 | 5:2 | 6:2 |
| 0:3 | 1:3 | 2:3 | 3:3 | 4:3 | 5:3 | 6:3 |
| 0:4 | 1:4 | 2:4 | 3:4 | 4:4 | 5:4 | 6:4 |
| 0:5 | 1:5 | 2:5 | 3:5 | 4:5 | 5:5 | 6:5 |
--->

    and   as     assert break   class  continue def
    del   elif   else   except  exec   finally  for
    from  global if     import  in     is       lambda
    not   or     pass   print   raise  return   try
    while with   yield
    
## Misc
gotchas, list comprehensions

    print # prints and empty line
    len(test)

## Resources/References
* https://www.python.org/
* http://www.codecademy.com/tracks/python
* 