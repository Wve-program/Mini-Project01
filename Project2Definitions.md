**Mini-Project 02 Definitions and Examples**

*How Python uses Indentation to control Flow*
	
Python uses Identation to control the flow of your code. What this does to the code is that it affects the
order in which the program that is being build is executed. 

     For example:
	 
	 def addition(a, b):
	     return float(a) + float(b)
			
This code example shows the definition of addition returning the basic function of A + B in the following line.
Indenting the code creates blocks, this is how Python programs gain a structure. Each indentation is a block and
a different place when the code is executed.  
			


*Don't Repeat Yourself*

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

*Design Patterns from Gang of Four*





Class



Object



Static



Property / Attribute



Method



Exception



Unit Test



Constructor



Factory



Decorator



Extend Class



CSV Files



Reading Files
