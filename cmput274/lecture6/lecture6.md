# Lecture 6

## Function

- Statments belonged together

- Use of function is come from experience

![](img_1.jpg)

### Built-in Functions

![](img_2.jpg)

- Concept of black box
	- Implementation detail (semantic, computation) is hidden (Information Hiding and Abstraction)

### Define Function

- Function identifier and its definition (lines of code / statement) are stored after being interpreted (no execution)

![](img_3.jpg)

### Pass Args, Return Value

- Argument(s) / Parameter(s) - local varibale(s) inside the function(s)

### Call Stack

refers to the fact that
- the local variable(s) of a function only live for the lifetime of that function called (there are methods that can access the local varibale(s) outside the function)
- once that returning from that function, the local variable(s) reaches the end of its lifetime in stack order (last in first out property)
- stack is poped

#### Example

![](img_4.jpg)

### Main Namespace

![](img_5.jpg)

- if .py file is imported, statement(s) under if __name__ == "__main__" will not be executed

### Local and Global Variables

![](img_6.jpg)

- Try to avoid using global variable

- name reuse, local varibale with the name same as the function is stored in different memory space / location when a function is called / invoked

- local varibale(s) hide the global one (try to avoid)

#### Example

![](img_7.jpg)

### Updating Global Variables

![](img_8.jpg)

- Modify a variable, it should be local variable (default)

![](img_9.jpg)

- breaking the information hiding

### Default Values

![](img_10.jpg)

- the order of passing args / params can be changed by invoking the name / keyword of args / params

### docstring

![](img_11.jpg)

## Modules

- Function(s) / Global variable(s) belonged together

![](img_12.jpg)

![](img_13.jpg)

module_name.function1()
	- module_name - general namespace
	- function1() - specific namespace / function

- from ... import ...
	- load the functions into the current namespace

- import
	- create a new namespace under the module's name

### __name__ == "__main__"

- Protect code

#### Example

![](img_15.jpg)
