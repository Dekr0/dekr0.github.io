# Lecture 4

## Circuit Analysis Using Lumped Component Approximation

![](img_1.png)

![](img_2.png)

- Battery is modeled by an indep. voltage source ($$V_0$$). can be viewed as "**lumped**" representation of the actual battery since all the **internal chemistry** of the battery is **ignored** and we are using the lumped value $$V_0$$

### Analysis (ECE 202)

A circuit or a system is given.

We are aksed to find out how the circuit or the system behaves (no assumption, no given information, everythin is unknown)

- **remark:** don't assume the direction of the current, don't consider positve and negative

### Synthesis (Opoosite of Analysis)

Desired circuit behavior (system behavior) is given

We are aksed to create the circuit (system) that exhibits such behavior

## Node

- In a **lumped model**, various lumped elements are connected each other by **perfectly conducting** (**zero resistance**) segments.

![](img_3.png)

![](img_4.png)

- Such zero resistance regions are called **nodes**.

- Within a node, there is **no change** in voltage.

- Each node has an unique "**node voltage**" which **does not vary from** one point to another winthin that node.

- **Shape** of the nodes can be **changed arbitrary** without **affecting the electrical variables** inside the circuit

**Important** : Circuit description (or circuit toplogy)
- How many nodes? (Label The Nodes)
- How the componenets are connected between those nodes?

#### Example

- Previous Example:
	- 6 nodes
	
![](img_5.png)

- Using this description, many different layouts can be for the same circuit.

#### Possible Alternative Layouts

![](img_6.png)

![](img_7.png)

**Important**
- Arrow directions mean the direction of travel (**no the direction of the current**, the direction of travel or path can be arbitrary)

or

![](img_8.png)

Although the connection and layout is different, it is same from the electrical point of view

Simplfy a cirucit with complicated layout into much more simple or clear one.

### Loop

A **loop** is any closed path through the circuit in which **no node** is encoutered **more than once**

### Mesh

The number of Mesh is not always the same (depends on the direction / way of travel?)

Mesh is a loop that does not **contain any other loop** within it. ("smallest size loop")
- strictly follow the characteristic of the loop

### Branch

Any **lumped element** can be viewed as a branch.

#### Examples

![](img_9.png)

- Purple, dark green, pink / red:  The direction of travel or path $$!=$$ the direction of the current

- Light green: Mesh

![](img_10.png)

- not a valid loop because 2 has been visited twice

- number of branches = 7

**Remark**:

- number of branches and # of nodes in a circuit are constants

### Kirchoff's Current Law (KCL)

Applied on nodes ...

$$\sum$$ Currents entering a given node = $$\sum$$ Currents leaving that node

Aet: Algebraic sum of all currents leaving a node is zero.

**Important:** A circuit with N nodes with have $$(N-1)$$ linearly indep. KCL equations

#### Example

![](img_11.png)

Write KCL for every node

![](img_12.png)

![](img_13.png)

Eqns (1) - (5): linearly dependent

Check:

![](img_14.png)

### Kirchoff's Voltage Law (KVL)

... applied on meshes and loops

Around any closed path (mesh and loop)

<center>
$$\sum$$ Voltage drop = $$\sum$$ Voltage rise
</center>

Aet: Around any closed patgh (meshes and loops) algebraic sum of all voltage rise (or drop) is **zero**

#### Example

![](img_15.png)

- red - meshes

- green - loop and direction of travel

**Important**
- Arrows mean direction of Travel (NOT the direction of current)

KVL for **inside the loop** (Meshes)

**Left Mesh**: A - B - E - F [Direction of travel does not matter]

KVL:

![](img_16.png)

**Rigth Mesh**:

KVL:

![](img_17.png)

![](img_20.png)

KVL **around the outer loop**

![](img_18.png)

**Important**
- Note that Eq(1) + Eq(2) $$\rightarrow$$ Eq(3). All these KVL equations are not linearly indep.
- In a circuit with N nodes and B branches, # of indep. KVL equations $$= B - N + 1$$ 

check:

![](img_19.png)
