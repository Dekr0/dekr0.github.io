# Lecture 2

## Limits

### Definition (not required)

![](img_1.png)

- Limit of $$f(x,y)$$ as $$(x,y)$$ approaching $$(a,b)$$ equals to number $$L$$ where $$f(x,y)$$ is being as close as number $$L$$

- $$\sqrt {(x-a)^2+(y-b)^2} \rightarrow$$ in 2D is a circle

- $$\delta \rightarrow$$ radius of the circle

![](img_2.png)

- If value for point $$(x,y)$$ is in domain $$D$$ and is within a circle whose origin is $$(a,b)$$ has a radius $$\delta$$, point falls in interval of $$L - \epsilon$$ and $$L + \epsilon$$

- The disntance of $$f(x,y) - L$$ is always smaller than $$\epsilon$$

**Side Note**:

<center>$$|f(x,y) - L| < \epsilon$$</center>

<center>$$-(f(x,y) - L) < \epsilon$$ and $$f(x,y) - L < \epsilon$$</center>

<center>$$L - \epsilon < f(x,y) < L + \epsilon$$</center>

**Remark**:

- $$|f(x,y) - L|$$ only describe the distance between number f(x,y) and L

![](img_3.png)

#### Example (limit do not exist)

General Solution:
- path approach method
	- choose a function that represent a curve or path (line, parabola, etc.)
	- curve / path should cross point $$(a,b)$$
	- choose the curve / path that is relatively simple to approach $$(a,b)$$

**Example 1.1**:

![](img_4.png)

- Solution

![](img_5.png)

Let y

<center>$$y = kx$$</center>

then replace $$y$$ in $$f(x,y)$$ with $$kx$$

<center>$$f(x,y) = f(x,kx) = ... = \frac {k^2}{1+k^4x^2}x$$</center>

calculate the limit as x approach to $$0$$ 

<center>$$\lim\limits_{x \to 0}f(x,kx)$$ = 0</center>

Let x

<center>$$x = y^2$$</center> 

then

<center>$$f(x,y) = f(y^2, y) = ... = \frac {1}{2}$$</center>

<center>$$\because \frac {1}{2} \neq 0$$</center> 

<center>$$\therefore$$ Limit D.N.E by definition</center>

**Example 1.2**:

![](img_5_2.png)

- Solution
	- use **horizontal line / vertical line to approach** to approach $$(a,b)$$ (even $$x$$, $$y$$ axis)

![](img_5_3.png)

**Example 1.3**:

![](img_5_4.png)

**Remark**:
- always assume $$(x,y,z)$$ is always close to $$(a,b,c)$$, which is $$(x,y) \neq (a,b)$$
- sometimes, it is better not to directly calculate the limit by substitue the coordinates of limit point (estimate by looking functions' graph)

- Solution

![](img_5_5.png)

**Example 1.4**: 

![](img_5_6.png)

- Solution
	- use line with a specific slope $$y = kx$$ 
	- L. hospital rule

![](img_5_7.png)

#### Examples (limit do exist)

General Solution:
- use path approach method to determine whether if the limit exist
- if the limit exist and can be calculated, the limit from calculation is "**supspect limit**"
	- prove the supspect limit: use either $$\epsilon ~ \delta$$ definition or **Squeeze theorm**

- Example 1 :

![](img_6.png)

- Solution

![](img_7.png)

- apply Squeeze Th.
	- take a function similared to $$f(x,y)$$ (omit the $$x^2$$ term in the bottom)
	- compare with the original function

**Side Note**:

- abs. value of term with even degree is same as the original term

![](img_8.png)

## Continuity

![](img_9.png)

**Notes** (not a single cond.):
- $$f(a,b)$$ must exist, that is, $$(a,b) \in D_f$$ (domain)
- $$\lim\limits_{(x,y) \to (a,b)}$$ must exist
- If both **exist**, they must be equal

#### Examples

![](img_10.png)

- Solutions

![](img_11.png)

![](img_12.png)

### Remark: Polar Coordinates

![](img_13.png)
