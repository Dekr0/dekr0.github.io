# Lecture 5

## Common Circuit Connections

1. Series connection
2. Parallel connection
3. Y connection (aka "star" connection)
4. delta connection

### Series Connections

![](img_1.jpg)

Two conditions both need to be satisified:

- Elements **must** be connected **end- to -end** with one common node

- **Same current** (or **same charge**) must physically flow through each element. No part of the current **escapes** and no new current is added


#### Example

![](img_2.jpg)

- Elements 1, 2, 3 are in series

- Elements 4 and 5 are in series

- Elements 3 and 4 are not in series

#### Cases I:

![](img_3.jpg)

- A voltage source and two resistors are in series
	- $$V_0$$ is the active element

- Apply KVL: $$V_0 = V_{R_1} + V_{R_2}$$

![](img_4.jpg)

- Applied voltage gets divided across the resistors
	- "**Votage Divider**" circuit

![](img_5.jpg)

**Applied voltage** $$V_0$$ is divided in direct proportion of the resistors

From the viewpoint of the voltage source, $$R_1$$ and $$R_2$$ in series is reuivalent ot having a single resistor $$R_eq (= R_1 + R_2)$$

![](img_10.jpg)

- From the viewpoint of the voltage source, $$R_1$$ and $$R_2$$ in series is equivalent to having **a single resistor** $$R_eq (= R_1 + R_2)$$

**Generalize case I** 

![](img_11.jpg)

![](img_12.jpg)

**Example** 

![](img_13.jpg)

#### Practical Application: Potentionmeter

aka "**Pot**"

Ex: We have 10 V (Specification, not actual) battery. Need 4V

![](img_6.jpg)

![](img_7.jpg)

- As the slider moves, the ratio of $$R_1$$ and $$R_2$$ change but $$R_1 + R_2$$ remains constant

![](img_8.jpg)

![](img_9.jpg)

#### Case II

- m voltage sources and m resistors in series

Ex:

![](img_14.jpg)

- Both "I" and its direction are assume

![](img_15.jpg)

#### Example

![](img_16.jpg)

Find $$I_0$$ and find $$V_{bc}$$ (Voltage across $$20K \Omega$$)

Solution

- Find $$R_{eq}$$ and $$V_eq$$ 

$$R_{eq} = 10 + 20 + 30 = 60 K \Omega$$

$$V_{eq} = 12 - 6 = 6 $$

$$-I_0 = - \frac {6}{60} = -0.1 mA$$ (Notice that the "-" sign is because the direction of travl of eq. diagram is reversed from the orginal

![](img_17.jpg)

Solution (Without redirect the direction of the travel)

![](img_18.jpg)

### Parallel Connection

![](img_19.jpg)

- Two or more than two lumped elements are in parallel when they are connected between the same pair of nodes

- Vlotage across each element is the same: 

![](img_20.jpg)

- Elements 1 and 2 are in parallel
- Elements 3 and 4 are in parallel
- However, elements 2 and 3 are not in parallel
	- element 2 is connected between node A and C
	- element 3 is connected between node B and C

#### Case I

![](img_21.jpg)

- n resistors and a current source in parallel

KCL @ A: $$I = I_1 + I_2 + ... + I_n$$

![](img_22.jpg)

- Supply current is divided into smaller parts $$\rightarrow$$ **Current divider**

![](img_23.jpg)

**Important** 

![](img_24.jpg)

- Current is divided in the inverse proportion of the resistor value (Resistor with smaller value will carry larger share of the current)

- $$I_n = \frac {V_{AB}}{R_n} = \frac {R_{eq}I}{R_n} = \frac {R_{eq}}{R_n} I$$

- $$R_n$$ is the total resistance in the specific branch of the parallel circuit

#### Speical case

- Suppose one of the resistors is 0 $$\Omega$$ (Say $$R_n = 0 \Omega$$)

![](img_25.jpg)

- Resistors are "shorted" by $$R_n = 0 \Omega$$ 

![](img_26.jpg)

[Current take the least resistance path and flows entirely through $$R_n = 0$$ by passing all other resistors] 
