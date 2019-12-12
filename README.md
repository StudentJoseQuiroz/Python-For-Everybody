# Python for Everybody Specialization

## Goals </br> 

 - Complete the Python for Everybody Specialization

## Boundaries / Scope </br>

 - Complete Course 1 Programming for Everybody (Getting Started with Python)</br>
 - Complete Course 2 Python Data Structures</br>
     		 
## Success criteria </br>

 - My own application for data retrieval and processing.
 - Weekly work log with screenshots and summaries to demonstrate activity.

## Constraints </br>

 - I will be auditing the course for free so will be able to read and view the course content but not submit projects or earn the certification.

## Assumptions </br>

- The courses will be available for the duration of the semester.
- I have all required software.
- I can skip the Installing and Using Python units.

## Stakeholders </br>

 - Professor - for my grade in class
 - Parents - investing in my education and future success, I want to make them proud
 - Perspective Employers - artifact will be added to my student portfolio which could help with getting a job
 - Myself - to gain knowledge in the computer science field

## Timeline </br>

Weekly Chapters:

 - Chapter One - Why we Program? (3 hours) </br>
	- There are many reasons why we program. Some important and common reasons are:
		- [ to build websites, apps, or maybe even use to acquire data within your career field] 
	- In the first chapter, we go over basic hardware and it's main properties
		- The Central Processing Unit: runs the program, aka CPU, and is always wondering "what to do next". A very fast property.
		- Input Devices: include the keyboard, mouse, and touch screen feature
		- Output Devices: include screen, speakers, printer, DVD burner
		- Main Memory: is a fast small temporary storage - lost on reboot- aka RAM
		- Secondary Memory: is a slower large permanent storage - lasts until deleted - disk drive/memory stick
		- Below is a screenshot of a basic outlook on these properties:
			![pic1](file:///Users/sweet/Desktop/Screen%20Shot%202019-10-19%20at%205.09.30%20PM.png)
	- As the chapter continues on, different ways of installing Python 3 are demonstrated as well as how to take a screenshot of your work using "snipping tool" in windows and jEdit in macintosh
	- Following through the chapter, we start practicing writing codes in Python
		- Some basic patterns that we use are
			- Sequential Steps
				- file:///Users/sweet/Desktop/Screen%20Shot%202019-10-19%20at%206.01.14%20PM.png
			- Conditional Steps
				- file:///Users/sweet/Desktop/Screen%20Shot%202019-10-19%20at%206.03.22%20PM.png
			- Repeated Steps 
				- file:///Users/sweet/Desktop/Screen%20Shot%202019-10-19%20at%206.04.24%20PM.png
	- Something very useful that chapter one goes through as well are some reserved words that cannot be used as names for variables/identifiers
		- file:///Users/sweet/Desktop/Screen%20Shot%202019-10-19%20at%205.56.28%20PM.png
		
 - Chapter Two: Variables and Expressions (3 hours) </br> 
	 - Chapter 2 is introduced with the concept of what constants, variables and assignment statements(consisted within the statement) are:
		 - Constants are fixed values such as numbers, letters, and strings
			 - they are called constants because they do not change
		 - Variables are a named place in the memory where a programmer can store data and later retrieve the data using the variable "name"'
		 - Assignment statements consist of an "expression" on the right-hand side and a variable to store the result
			 - we assign a value to a variable using the assignment statement "="
	- Some basic numeric expressions in Python are displayed in the image below:
		- file:///Users/sweet/Desktop/Screen%20Shot%202019-10-19%20at%207.02.32%20PM.png
	- It is also very important to keep in mind that Python uses operating precedence rules, aka PEMDAS, when operating with numerical functions
		- file:///Users/sweet/Desktop/Screen%20Shot%202019-10-19%20at%209.01.07%20PM.png
	- Overall, Chapter focuses on going over constants, variables, reserved words, type, mnemonic variable names, operators, operator precedence, type conversion and comments and then writing an entire program.
	
 - Chapter Three: Conditional Code (3 hours) </br> 
	 - In this chapter, we start off by focusing on condition statements/execution, where we start adding in more "intelligence" into the coding.
	 - We get to go over the differences and areas of complexity between different decision ways of coding. Below are the different examples:
		 - one-way decision:
			 - file:///Users/sweet/Desktop/Screen%20Shot%202019-11-19%20at%2011.08.36%20AM.png
		 - two-way decision:
			 - file:///Users/sweet/Desktop/Screen%20Shot%202019-11-19%20at%2010.26.45%20AM.png
		 -  nested decision:
			 - file:///Users/sweet/Desktop/Screen%20Shot%202019-11-19%20at%2010.21.19%20AM.png
		 - multi-way decision:
			 - part 1:
				 - file:///Users/sweet/Desktop/Screen%20Shot%202019-11-19%20at%2010.32.34%20AM.png
			 - part 2 (another way to use multi-way decision coding, different variations, no else or numerous elifs & else):
				 - file:///Users/sweet/Desktop/Screen%20Shot%202019-11-19%20at%2010.35.02%20AM.png
			 - try and except:
				 - file:///Users/sweet/Desktop/Screen%20Shot%202019-11-19%20at%2011.03.12%20AM.png
	- Key coding methods to focus on in this chapter are;
		- if/else: a conditional statement that runs a different set of statements depending on whether an expression is true or false
		- if/elif/else: same as if/else except that after the if there are elif statements that stand for else if, meaning if the condition for "if" is false , it checks the condition of the next "elif" block and so on. If all the conditions are false, including the "elifs", then the body of "else" is executed
		- try and except block: a try block lets you test a block of code for errors. The except block lets you handle the error. The final block lets you execute code, regardless of the result of the "try- and except" blocks.
	- Another useful thing that chapter 3 goes over are some comparison operators to keep in mind when coding:
		- file:///Users/sweet/Desktop/Screen%20Shot%202019-11-19%20at%2011.10.36%20AM.png
	- In conclusion, this chapter goes through and discusses one-way decisions with if, two-way decisions with if-then-else, nested decisions where you have an if inside of an if that moves on in, else-if, and then try and except to catch errors that you want to catch them.

 - Chapter Four: Functions (2 hours) </br>
	 - In the start of this chapter, the fact about storing and reusing is addressed. Dr. Chuck goes over how programmers do not like to repeat themselves so they store and reuse these functions.
		 - functions: reusable pieces of code
			 - Below is an example displayed of assigning functions to a new keyword "def" that stands for start the definition of a function. To run a defined function, you must call it by writing the keyword of followed by "()"
			 - file:///Users/sweet/Desktop/Screen%20Shot%202019-11-19%20at%2011.21.26%20AM.png
		- parameter: a variable which we use in the function definition. It is a "handle" that allows the code in the function to access the arguments for a particular function invocation.
		- return values: often a function will take its arguments, do some computation, and return a value to be used as the value of the function call in the "calling expression" and the return keyword is used for this.
		- max functions: a chunk of code that's been built into Python before, passing in an argument, which is a string. There is some code inside that runs through the argument, comes in and then it looks/reads through the information, and then sends us back the answer, which is this is called a return.
			- file:///Users/sweet/Desktop/Screen%20Shot%202019-11-20%20at%2012.25.49%20PM.png
		- type conversions:
			- file:///Users/sweet/Desktop/Screen%20Shot%202019-11-20%20at%2012.39.51%20PM.png
		- string conversions:
			- file:///Users/sweet/Desktop/Screen%20Shot%202019-11-20%20at%2012.40.31%20PM.png
	- In conclusion, a function is some bit of reusable code, we define a function using a def keyword, and then we call or invoke it. Some functions do not return values. We call them non-fruitful functions, and if they return values then we call them fruitful functions.
	
 - Chapter Five: Loops and Iteration (3 hours) </br> 
	 - Each time we execute the body of the loop, we call it an iteration.
	 - We call the variable that changes each time the loop executes and controls when the loop finishes the iteration variable. If there is no iteration variable, the loop will repeat forever, resulting in an infinite loop.
		 - Loop with iteration variable affected:
			 - file:///Users/sweet/Desktop/Screen%20Shot%202019-11-20%20at%201.03.48%20PM.png
		- Loop without iteration variable affected, resulting in an infinite loop:
			- file:///Users/sweet/Desktop/Screen%20Shot%202019-11-20%20at%201.07.55%20PM.png
		- You can break out of a loop with the executable statement "break"
			- file:///Users/sweet/Desktop/Screen%20Shot%202019-11-20%20at%201.16.09%20PM.png
		- Below are some tips for making a smart loop
			- file:///Users/sweet/Desktop/Screen%20Shot%202019-11-20%20at%202.49.25%20PM.png
	- In conclusion, in this chapter we focus on some definite loops, some indefinite loops, how to break to get out of loops, continue to pop back up. We continue works in for loops as well as while loops/iteration variables, how with "while" loops you construct them yourself and in "for" loops, "for" constructs them for you.

 - Chapter Six: Strings (3 hours) </br> 
	 - For starters, Chapter 6 starts off with talking about strings and reading data from input. 
		 - string: a sequence of characters
		 - Images below show string data type and different input reading and converting
		 - numbers must be converted from strings
			 - file:///Users/sweet/Desktop/Screen%20Shot%202019-11-26%20at%2011.58.19%20PM.png
			- file:///Users/sweet/Desktop/Screen%20Shot%202019-11-27%20at%2012.02.27%20AM.png
		- something to keep in mind is that you will get a python error if you attempt to index beyond the end of a string
		- built-in function len gives length of a string 
		- using a while statement and an iteration variable, and the len function we can construct a loop to look at each of the letters in a string individually
		- Below is an image that shows looping through strings
			- file:///Users/sweet/Desktop/Screen%20Shot%202019-11-27%20at%2012.11.12%20AM.png
	- Chapter 6 continues on towards a conclusion by showing how strings can be manipulated
		- number manipulation is one kind of program and string manipulation is generally another thing that we do in programs
		- when the "+" is applied to strings concatenation
		- and below we see "in" used as a logical operator
			- file:///Users/sweet/Desktop/Screen%20Shot%202019-11-27%20at%2012.33.43%20AM.png

 - Chapter Seven: Files (3 hours) </br> 
	 - Chapter 7 begins with talking about what we've been over so far through the course of python by showing us one of the first diagrams we started off with and going forward with the fact that it's time to look at some data
		 - file:///Users/sweet/Desktop/Screen%20Shot%202019-11-27%20at%201.14.11%20AM.png
		 - A text file can be thought of as a sequence of lines
			- when you want to read a file, we have to tell python which file to open
			- file:///Users/sweet/Desktop/Screen%20Shot%202019-11-27%20at%201.17.07%20AM.png
		- Below is an example of using "open()"
			- file:///Users/sweet/Desktop/Screen%20Shot%202019-11-27%20at%201.22.52%20AM.png
		- we also learn about the newline character "\n" that is one character, not two
			- file:///Users/sweet/Desktop/Screen%20Shot%202019-11-27%20at%201.23.36%20AM.png
		- Moreover, after learning how to open files we will now learn how to read the file through a file handle
			- a file handle to the for loop looks like a sequence of lines, it's a sequence of lines
			- not the same as putting the string there, for loop is smart
			- the for loop is going to run this code multiple times where the iteration variable, cheese in this case, is going to take on the successive lines, if this file has 10 lines, this loop is going to run 10 times. Cheese is going to be the first line, the second line, third line
			- file:///Users/sweet/Desktop/Screen%20Shot%202019-11-27%20at%201.38.54%20AM.png
			- We then continue forward counting the lines in a file, by reading the file as a "whole" and then prompting for the file name:
			- counting: file:///Users/sweet/Desktop/Screen%20Shot%202019-11-27%20at%201.41.30%20AM.png
			- reading: file:///Users/sweet/Desktop/Screen%20Shot%202019-11-27%20at%201.41.42%20AM.png
			- prompting: file:///Users/sweet/Desktop/Screen%20Shot%202019-11-27%20at%201.46.56%20AM.png

 - Chapter Eight: Lists (3 hours) </br>
	 - Chapter 8 is a brief chapter on lists
		 - starts with the reminder that
			 - algorithms are set of rules or steps used to solving problem
			 - data structures are particular ways of organizing data in a computer
		- lists are kind of a collection
			- file:///Users/sweet/Desktop/Screen%20Shot%202019-11-27%20at%201.54.48%20AM.png
			- we use commas to separate them and brackets to start and end them
			- some lists constants below
			-  file:///Users/sweet/Desktop/Screen%20Shot%202019-11-27%20at%201.56.09%20AM.png
				- strings are immutable, we cannot change the contents of a string. we must make a new string to make any change
				- lists are mutable we can change an element of a list using the index operator
				- the len() function takes a list as a parameter and returns the number of elements in the list
				- actually len() tells us the number of elements of any set or sequence (such as string...)
		- We move onto manipulating lists:
			- we can have splice lists with the ":" symbol:
				- file:///Users/sweet/Desktop/Screen%20Shot%202019-11-27%20at%202.04.16%20AM.png
			- we can build lists from scratch:
				- file:///Users/sweet/Desktop/Screen%20Shot%202019-11-27%20at%202.06.12%20AM.png
			- we can have built-in lists:
				- file:///Users/sweet/Desktop/Screen%20Shot%202019-11-27%20at%202.05.56%20AM.png
		- Then we end the chapter connecting lists and strings:
			- split breaks a string into parts and produces a list of strings. 
			- we think of these as words, we can access a particular word or loop to all of the words
			- when you do not specify a delimiter, multiple spaces are treated like one delimiter
			- you can specify what delimiter are character to use in the splitting
		- Example of List Summary
			- file:///Users/sweet/Desktop/Screen%20Shot%202019-11-27%20at%202.06.12%20AM.png

 - Chapter Nine: Dictionaries (3 hours) </br>
	 - For starters, dictionaries are our second data structure.
		 - we briefly go over collections in the beginning of this chapter:
			 - file:///Users/sweet/Desktop/Screen%20Shot%202019-11-27%20at%202.20.51%20AM.png
		- Dictionaries or Python's most powerful data collection
		- Dictionaries allow us to do fast data base like operations in Python
		- Dictionaries have different names in different languages
		- For example:
			- Associative arrays - Perl/PHP
			- Properties or Map or HashMap - Java
			- Property bag - C#/.Net
		- Lists index their entries based on the position in the list
		- Dictionaries are like bags - No order
		- So we indexed the things we put it in the dictionary with a "lookup tag"
		- Dictionaries are like lists except that they use keys instead of numbers to look up values
		- One many common use of dictionaries discounting how often we "see" something
		- file:///Users/sweet/Desktop/Screen%20Shot%202019-11-27%20at%202.35.46%20AM.png
		- When we encounter a new name, we need to add a new entry in the dictionary and if this is a second or later time we have seen the name,'s we simply add one to the count in the dictionary under that name
		- Below is the get method for dictionaries
			- file:///Users/sweet/Desktop/Screen%20Shot%202019-11-27%20at%202.38.23%20AM.png
			- Even though dictionaries are not stored in order, we can write a for loop that goes through all the entries in a dictionary - actually go through all of the keys in the dictionary and looks up the values
			- View of tuple in upcoming chapter
				- file:///Users/sweet/Desktop/Screen%20Shot%202019-11-27%20at%202.42.48%20AM.png

 - Chapter Ten: Tuples (2 hours) </br>
	 - Chapter 10 is a brief chapter on tuples
		 - Tuples are another kind of sequence that functions much like list- they have elements which are indexed starting at zero
		 - Unlike a list once you create a tuple, you cannot alter its contents, similar to string
		 - We can also put it tuple on the left-hand side of an assignment statement, we can even omit the parentheses
		 - Tuples are comparable
			 - file:///Users/sweet/Desktop/Screen%20Shot%202019-11-27%20at%203.01.04%20AM.png
			 - We can take advantage of the ability to sort a list of tuples to get a sorted version of a dictionary, but first we sort the dictionary by the key using the items() method and sorted() function
			 - sorted()
				 - file:///Users/sweet/Desktop/Screen%20Shot%202019-11-27%20at%203.04.15%20AM.png

 - Graduation and work on independent program (2 hours) </br>
	 - Throughout this time I completed my graduation videos of my audited version of course 1 and 2 of Python for Everybody by Dr. Charles Russell Severance, my online instructor throughout both courses.
	 - I was also able to utilize my time and focus on bringing my integration program a bit more together by using information I obtained throughout both courses

 - Complete independent program (2 hours) </br> 
	 - I utilized my time to complete my independent integration program and revise through my coding
	 - I also had peers test and revise my program as well for better program efficiency and non-biased critique
