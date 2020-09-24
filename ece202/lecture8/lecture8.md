# Lecture 8

## Measurement Equipments (Labs)

**Multi-meter** 

- current measurement - Ammeter (ampere-meter)

- voltage measurement - Voltmeter

- Resistance mesurement - Ohmmeter

### Ammeter

- Measures current

- Theoratically $$I = \frac {V_0}{R}$$

- How to connect an ammeter to this circuit so that it measure the current I?
	- Ammeter needs to be placed in **series** with the component of interest

- Current $$\rightarrow$$ flow of charge $$\rightarrow$$ "current sensor" or ammeter need to be placed within the "flow"

- **Measurement Diagram**

- Ammeter is an electronic equipment and has some internal resistance say $$R_{ammeter}$$ 

- **Circuit Diagram**

- Calculate $$I_{measured}$$

- known as loading effect of the ammeter

- For an ideal ammeter, $$R_ammeter = 0$$

### Voltmeter

- Measures voltage

- Theoretically $$V_{R2} = \frac {R_2}{R_1+R_2}V_0$$

- If want to measure $$V_{R_2}$$
	- then $$V_{R_2} = V_A - V_B$$
	- voltmeter needs to be connected between A and B or in parallel with $$R_2$$

- **Measurement Diagram**

- If $$R_{voltmeter} \rightarrow$$ infinity, then $$R_2$$ || $$R_{voltmeter} \rightarrow R_2$$

- Ideal voltmeter should have inifinity internal resistance or it should behvae liek an open-circuit

### Ohmmeter

- Measures resistance

- Ohmmeter has internal power source (voltage or current)

- Ohmeter calculate $$\frac {V_{ohmmeter}}{I_{ohmmeter}} = R^{eq}_{AB}$$

- Ohmmeters have internal resistance - loading effect
	- To minimize this, $$R_{ohmmeter}$$ should be as small as possible

## Standard Circuit Analysis Techniques

- A circuit is given, find all the voltages and current

1. Nodal Analysis
2. Mesh analysis or loop analysis

### Nodal Analsys

- **General procedure**
- (1)
	- circuit with n nodes, $$(n-1)$$ linearly indep. KCL equations
	- choose one of the nodes as "reference" aka "ground" and every other node voltage is measured W.R.T this reference

	- Reference node is indicated by the follwoing

	- Rule of thumb: if ref. node is not specified, pick the node that is most "**common**" among all the elements
		- connected with max number of branches

	- Then write KCL equations at the remaining $$(n-1)$$ non ref. nodes
- (2) Define node voltages $$V_1, V_2, ... V_{n-1}$$ w.r.t to ground
- (3) Write KCL equations at each non ref. nodes by using node voltage vars
- (4) we have $$n-1$$ linearly indep. KCL equations
	- solve for the unknowns $$V_1, V_2, ... , V_{n-1}$$

#### Different Scenarios:

- Scenario 1: Resistive network powered by indep. current sources only

**Example 1**

- Scenario 2: Resistive netowrk powered by indep. & dep. current sources

- Scenario 3: Circuit powered by indep. or dep. voltage sources, with one node connected to ground
