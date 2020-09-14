# Lecture 4

## Built-In Type: list

![](img_1.png)

### Sample List Methods

![](img_2.png)

pop - treat list as stack
	- stack - data strcuture, last in first out

### List and Strings

![](img_3.png)

## Decision Making

### Motivation

![](img_4.png)

### Pseudocode

Flow Chart

![](img_5.png)

### Python

![](img_6.png)

### "if" Statement

![](img_7.png)

### "if/else" Statement

![](img_8.png)

![](img_9.png)

### "if/elif/else" Statement

if - first conditional test

elif - second or further conditional test (chain)

else - unconditional test

**Remark (Improve code quality):** 
- make it as short as possible (as simple as possible)
- rethink if/elif/else statement, redesign / simplfy the statment 

![](img_10.png)

### Nested "if" Statements

![](img_11.png)

Question: Use iteration to simply this problem

### Comparing Decimal Numbers

**Remark:** 
- floating point are not repeated
- finite number of digits, precision, and other important properties
- Never compare two floating point for equality (whether is closer together / with tolerance instead)
**Remark:** 

- if nest more than 1 extra level, too complicated and try to simplfy it

## Iteration

### Loops

![](img_12.png)

It is able implement any for loop with while loop that they are equivalent.

Only need one type of loop needed for computability

However, for convenience, both loops exist.

### for Loop

- **iterator** 

#### Example

![](img_13.png)

variable **word** is being reused (assigned to a new value in each iteration)

### range()

![](img_14.png)

**Remark:** 

- using index to access the iterable object is more common in language in C / C++
- somtimes, it is necessary to use indices instead the value / the element especially using parallel list / array, items or elements have some special relationship between different lists / arrays
	- require indices to access multiple lists / arrays at the same time

### while Loop

#### Example - Sentinel Value

![](img_15.png)

#### break

break can be error (better sentinel or other flags)

## **random** Module

dir() - print out all the identifier

namespace - what variables are visible in python
