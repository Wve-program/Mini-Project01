**Mini-Project 02 Definitions and Examples**

**How Python uses Indentation to control Flow**
	
Python uses Identation to control the flow of your code. What this does to the code is that it affects the
order in which the program that is being build is executed. 

     For example:
	 
	 def addition(a, b):
	     return float(a) + float(b)
			
This code example shows the definition of addition returning the basic function of A + B in the following line.
Indenting the code creates blocks, this is how Python programs gain a structure. Each indentation is a block and
a different place when the code is executed.  
			


**Don't Repeat Yourself**

Also known as *DRY* don't repeat yourself is a principle in software development that looks into reducing repetition in coding. 
Repeating lines of code that state the same thing looks messy and unprofessional. Following DRY and reducing the repetition 
reinforces a neat code. 

     For example:
	 
	 subject1 = [1, 10]
	 subject1 = [11, 20]
	 subject1 = [21, 30]
	 subject1 = [31, 40]
	 subject1 = [41, 50]
	 
	 A cleaner for this to look would be;
	 
	 subjects = [[1, 1, 10],
		    [2, 11, 20],
		    [3, 21, 30],
	            [4, 31, 40],
	            [5, 41, 50]]
				 
Instead of having to list a subject for each data set, They could be grouped together and form one group of subjects that are separated
by saying subjects first then establishing which is which in the bracket.

**Design Patterns from Gang of Four**

The *Gang of Four* is actually a reference to the four authors who wrote the patterns; Erich Gamma, Richard Helm, Ralph Johnson, and John Vlissides.
The four individuals wrote patterns for programming which are; Creational Patterns, Structural Patterns, and Behavioural Patterns. 

     Creational Patterns gives ways to instantiate objects of related objects. 
	 The list of patterns for creational patterns:
	 
     Abstract Factory
	 Builder
	 Factory Method
	 Prototype
	 Singleton

     Structural patterns gives a method to define relationships between classes or objects Class.
     Structural Patterns include: 
	 
	 Adapter
	 Bridge
	 Composite
     Decorator
	 Facade
	 Flyweight
	 Proxy
	 
	 Behavioural Patterns define manners of communication between classes and objects.
	 A list of Behavioural Patterns: 
	 
	 Chain of Responsibility
	 Command
	 Interpreter
	 Iterator
	 Mediator
	 Memento
	 Observer
	 State
	 Strategy
	 Template Method
	 Visitor

**Object**

An Object is an instance of a class. You can declare an object by taking it from a class such as this example:

     Tank = Sherman()
	 
	 This initializes the object Tank as an instance of the class Sherman.


**Static**

Static means, that the member is on a class level rather on the instance level. Static variables exist only in single 
instance per class and are not instantiated. For example: 

     class Sherman:
	     American = 2

American Is the Static Variable. 

**Property / Attribute**

Attributes are described by things such as; name, height, size and, age. Properties on the other hand are often described 
as; set, get, and delete methods. 

	 Tank = Sherman()
	 print(Tank.Sherman)



**Method**

In Python, a method is a function that is available for the object because of the object's type. In the example below
The method is established dictates that the method is really a function that is part of the class. 

     class Tanks:
     def my_method(self):
        print "This is a Tank"

     Tank = Sherman()
	 Tank.my_method()
	 
	 
**Exception**

An exception is similar to an error, but what it does is, it points out a disruption of the code during the execution.
     
	 try:
     print(x)
     except:
     print("An exception occurred") 

Since X isn't defined in this code, the code will throw an exception.

**Unit Test**

The unit test is the first phase of testing when testing software. The Unittests start on the smallest testable parts of the software are tested.
The reason behind this form of testing is to validate each unit of the software making sure it is performing as designed.

     class TestMyFunction(unittest.TestCase):
	       Def testMultiply(self):
		   a = 5
		   b = 5
		   expected = 25
		   actual = myfunctions.multiply(a, b)
		   self.assertEqual(expected,actual,"failed test for 5x5")
		   
This example is a basic test for a multiplication function. 


**Constructor**
Constructors are used for instantiating the object. The task of the constructor is to initalize assigned values to the data members of the class
when an object is created. In Python specifically the__init__() method is called the constructor and is always called when an object is created. 

     def __init__(self)
	 
	 Example of a python constructor.


**Factory**

The Factory method is a creational design pattern made by the four authors that provides an interface for creating objects in a superclass, but allows 
the subclasses to alter the type of objects that will be created.

**Decorator**

A decorator in Python is any obkect that is callable in python that is used to modify a class or a function. When referencing a function or classs it is passed 
to a decorator and the decorator returns a modified function or class. The Modified functions or classes usually contain calls to the original function or class.
A good example of a decorator is as follows:

     def my_decorator(func):
		 def wrapper():
		     print("What is this.")
		     func()
		     print("What is that.")
		 return wrapper
		 
	 def say_what():
         print("What?")

     say_what = my_decorator(say_what)

	 

**Extend Class**

The 

**CSV Files**



**Reading Files**
