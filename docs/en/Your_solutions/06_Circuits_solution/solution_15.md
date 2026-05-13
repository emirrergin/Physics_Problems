# 🧊 Physics Basics: The Resistor Cube Challenge

## 1. Problem Statement
we have a cube constructed from **12 identical resistors**, each with a resistance **$R$**, placed on its edges. 

**Task:** Determine the total equivalent resistance ($R_{eq}$) between **two opposite corners** (the space diagonal) of the cube.

---

## 2. Fundamental Physics Principle: Symmetry and Equipotentials
To solve a complex 3D network like this, we use the **Symmetry Method**. 

When current ($I$) enters one corner (Node A) and leaves from the diagonally opposite corner (Node B), it distributes itself symmetrically through the network. This allows us to identify **equipotential points**—nodes that have the same voltage—and "collapse" the circuit into a much simpler series-parallel model.



---

## 3. Step-by-Step Symmetry Analysis

Imagine a total current $I$ enters at the starting corner.

### Stage 1: The First Junction (Entry)
From the starting corner, the current has **3 identical paths** to follow. Due to symmetry, the current splits equally:
*   Each of these 3 resistors carries a current of $I/3$.
*   Equivalent resistance of this layer: **$R_1 = R/3$**



### Stage 2: The Middle Section
Each of those 3 paths then splits into **2 more paths** (totaling 6 paths in the middle of the cube). Again, due to symmetry, the current splits equally:
*   Each of these 6 resistors carries a current of $I/6$.
*   Equivalent resistance of this layer: **$R_2 = R/6$**



### Stage 3: The Last Junction (Exit)
Finally, these 6 paths merge back into **3 paths** to reach the exit corner.
*   Each of these 3 resistors carries a current of $I/3$.
*   Equivalent resistance of this layer: **$R_3 = R/3$**



---

## 4. Final Calculation
Since these three "layers" are effectively in series with each other relative to the total current flow, we sum them up:

$$R_{eq} = R_1 + R_2 + R_3$$
$$R_{eq} = \frac{R}{3} + \frac{R}{6} + \frac{R}{3}$$

To add them, we use a common denominator (6):
$$R_{eq} = \frac{2R}{6} + \frac{R}{6} + \frac{2R}{6} = \frac{5R}{6}$$

**Final Result:** 
$$R_{eq} = \frac{5}{6}R$$



---