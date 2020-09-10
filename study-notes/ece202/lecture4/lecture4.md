# Lecture 4

## Circuit Analysis Using Lumped Component Approximation

- In a lumped model, various lumped elements are connected each other by perfectly conducting (zero resistance) segments.

- Such zero resistance regions are called nodes.

- Within a node, there is no change in voltage.

- Each node has an unique "node voltage" which does not vary from one point to another winthin that node.

- Shape of the nodes can be changed arbitrary without affecting the electrical variables inside the circuit

**Important** : Circuit description (or circuit toplogy)
	- How many nodes? (Label The Nodes)
	- How the componenets are connected between those nodes?

Previous Example:
	![]

Using this description, man different layouts can be for the same circuit.

Possible Alternative Layouts

Although the connection and layout is different, it is same from the electrical point of view

Simplfy a cirucit with complicated layout into much more simple or clear one.

### Analysis (ECE 202)

A circuit or a system is given.

We are aksed to find out how the circuit or the system behaves (no assumption, no given information, everythin is unknown)
	- **remark:** don't assume the direction of the current, don't consider positve and negative

### Synthesis (Opoosite of Analysis)

Desired circuit behavior (system behavior) is given

We are aksed to create the circuit (system) that exhibits such behavior

### Loop

Arrow directions mean the direction of travel (**no the direction of the current**, the direction of travel or path can be arbitrary)

A **loop** is anay closed path through the circuit in which **no node** is **encoutered**
more than once

### Mesh

The number of Mesh is not always the same (depends on the direction / way of travel?)

Mesh is a loop that does not **contain any other loop** within it. ("smallest size loop")
	- strictly follow the characteristic of the loop

### Branch

Any lumped element can be viewed as a branch.

Prev. ex: # of branches = 7

### KCL

**Important:** A circuit with N nodes with have $$(N-1)$$ linearly indep. KCL equations

### KFL

**Important:** Note that Eq(1) + Eq(2) $$\rightarrow$$ Eq(3). All these KVL equations are not linearly indep.

In a circuit with N nodes and B branches, # of indep. KVL equations $$= B - N + 1$$ 
