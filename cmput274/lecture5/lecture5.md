# Lecture 5

Iterative development - develop and program iteratively 

C uses error return values that imply or mean an error have occured

Error like EOFError is not actually an "error" but considered as unexpected event or any kind in terms of Python Intepreter

Exception handling - Asynchronus
	- when an error happen, it may or may not be execute the code that is expected to be execute

Recall: I/O Redirection

- python3 count.the.p3.v1.py < words.1 - "<" will redirect the contents in words.l into this .py file.
	- Specifically, take the contents and uses it as stdin (standard input) of that .py file
	- When finish reading all the contents, a EOF then will be read in word.l file

Use a **function**, for better abstraction
	- In the future, using function to make it convenient to read input stdin (keyboard / file) or from a given file with different file name.
	- In this case, separate the try ... except statement which handle exceptions that happen in input from main, and put it a function. 
		- The goal is to provide a better abstraction or hide the fact of reading input from stdin, file, etc. 
	- Logically / In terms of design wise, try ... statment solve one problem, can be viewed as a natrual unit

Practice - Predict data frame from debugging for building up a better mental model of how Python Interpreter works

Filter (Unix / Linux)

- Pipeline

	- a series of processes / programs whose stdout of one process / program is redirected into stdin of another one, and then continues

Example

- cat words.1 | python3 split.line.p5.v1.py | python3 count.the.p4.v1.py
	- pipe the stdout of cat words.1 into stdin of "python3 split.line.p5.v1.py" (print the splited word line by line), then pipe the stdout into stdin of "python3 count.the.p4.v1.py"
	- redirecting from a running process (producer - consumer model)
	- or python3 split.line.p5.v1.py < words.1 | python3 count.the.p4.v1.py

- grep - global regular expression processing.
	- regular expression is a language or formal system specify the particular pattern wanted to search for
		- formal system is a set of rules that define something, and that once everyone understand the rule of the formal system, everyone has to agree with what's being defined in the rules in the formal system at different stages


Global frame - Global namespace

Instead of storing the entire definition of an function, it store an identifier that points to that function (object) in the memory 

static call sign (same call sign), dynamic invocation (multiple invocation, generate multiple different frames)

