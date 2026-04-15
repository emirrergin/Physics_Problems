# Physics Basics: Electrostatic Equilibrium

## 1. Problem Description
Find the equilibrium position for a test charge $q_3 = +1\text{ C}$ placed on a line between two fixed charges, $q_1 = +4\text{ C}$ and $q_2 = +9\text{ C}$, which are separated by a distance of $2\text{ m}$.

## 2. Given Data
* **Charge 1 ($q_1$):** $+4\text{ C}$
* **Charge 2 ($q_2$):** $+9\text{ C}$
* **Charge 3 ($q_3$):** $+1\text{ C}$ (The charge to be placed in equilibrium)
* **Total Distance ($L$):** $2\text{ m}$
* **Goal:** Find the distance $x$ from $q_1$ where the net force on $q_3$ is zero.

## 3. Physical Principles
For $q_3$ to be in **electrostatic equilibrium**, the net electric force acting on it must be zero ($\sum F = 0$). 

Since $q_1, q_2,$ and $q_3$ are all positive, $q_3$ will be repelled by both $q_1$ and $q_2$. For the forces to cancel out, $q_3$ must be placed between them so that the forces point in opposite directions.

**Coulomb's Law:**
$$F = k \frac{|q_a q_b|}{r^2}$$

## 4. Step-by-Step Solution

### Step 1: Define the Distances
Let $x$ be the distance from $q_1$ to $q_3$. 
Since the total distance between $q_1$ and $q_2$ is $2\text{ m}$, the distance from $q_3$ to $q_2$ must be $(2 - x)$.

### Step 2: Set Up the Equilibrium Equation
The force exerted by $q_1$ on $q_3$ ($F_{13}$) must equal the force exerted by $q_2$ on $q_3$ ($F_{23}$):
$$F_{13} = F_{23}$$
$$k \frac{q_1 q_3}{x^2} = k \frac{q_2 q_3}{(2 - x)^2}$$

### Step 3: Simplify the Equation
Notice that the Coulomb constant ($k$) and the magnitude of the test charge ($q_3$) appear on both sides and cancel out. This means the equilibrium position depends only on the source charges $q_1$ and $q_2$:
$$\frac{q_1}{x^2} = \frac{q_2}{(2 - x)^2}$$

### Step 4: Substitute Values and Solve
Plug in $q_1 = 4$ and $q_2 = 9$:
$$\frac{4}{x^2} = \frac{9}{(2 - x)^2}$$

To make the calculation easier, take the square root of both sides:
$$\sqrt{\frac{4}{x^2}} = \sqrt{\frac{9}{(2 - x)^2}}$$
$$\frac{2}{x} = \frac{3}{2 - x}$$

### Step 5: Cross-Multiply
$$2(2 - x) = 3x$$
$$4 - 2x = 3x$$
$$4 = 5x$$
$$x = \frac{4}{5}$$
**$$x = 0.8\text{ m}$$**

## 5. Conclusion
The equilibrium position for charge $q_3$ is **$0.8\text{ m}$ away from charge $q_1$** (which corresponds to $1.2\text{ m}$ away from charge $q_2$).

> **Note:** Because $q_2$ is stronger than $q_1$, the equilibrium point is logically closer to the weaker charge ($q_1$) to compensate for the difference in charge magnitudes.