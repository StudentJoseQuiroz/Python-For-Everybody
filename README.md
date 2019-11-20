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
			- file:///Users/sweet/Desktop/Screen%20Shot%202019-10-19%20at%205.09.30%20PM.png
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
	 - For starters, 
 - Chapter Seven: Files (3 hours) </br> 
 - Chapter Eight: Lists (3 hours) </br>
 - Chapter Nine: Dictionaries (3 hours) </br>
 - Chapter Ten: Tuples (2 hours) </br>
 - Graduation and work on independent program (2 hours) </br>
 - Complete independent program (2 hours) </br> 
