# Physics Basics: Electric Potential (Square Configuration)

## 1. Problem Description
Four point charges of $+1\text{ C}, -2\text{ C}, +3\text{ C}$, and $-4\text{ C}$ are placed at the corners of a square with sides of $1.0\text{ m}$ in order. Calculate the total electric potential ($V$) at the center of the square.

## 2. Given Data
* **Charges ($q$):** $q_1 = +1\text{ C}$, $q_2 = -2\text{ C}$, $q_3 = +3\text{ C}$, $q_4 = -4\text{ C}$
* **Side Length ($a$):** $1.0\text{ m}$
* **Coulomb's Constant ($k$):** $\approx 8.99 \times 10^9\text{ N}\cdot\text{m}^2/\text{C}^2$
* **Goal:** Find total potential $V_{total}$ at the center.

## 3. Physical Principles
Electric potential is a **scalar** quantity. The total potential at a point due to a collection of point charges is the algebraic sum of the potentials due to each individual charge.

**Formula for Electric Potential:**
$$V = k \frac{q}{r}$$

**Superposition Principle (Scalar):**
$$V_{total} = V_1 + V_2 + V_3 + V_4 = k \sum \frac{q_i}{r_i}$$

## 4. Step-by-Step Solution

### Step 1: Geometry Analysis
Since the point of interest is the center of the square, the distance ($r$) from each corner to the center is the same for all four charges.
* Diagonal of the square ($d$): $d = a\sqrt{2} = 1.0\sqrt{2}\text{ m}$
* Distance to center ($r$): $r = \frac{d}{2} = \frac{\sqrt{2}}{2} \approx 0.707\text{ m}$

### Step 2: Simplify the Summation
Because $r$ is constant for all charges, we can factor out $k$ and $r$ from the summation:
$$V_{total} = \frac{k}{r} (q_1 + q_2 + q_3 + q_4)$$

### Step 3: Calculate the Net Charge
$$\sum q = (+1\text{ C}) + (-2\text{ C}) + (+3\text{ C}) + (-4\text{ C})$$
$$\sum q = -2\text{ C}$$

### Step 4: Final Calculation
Now, substitute the values into the simplified formula:
$$V_{total} = \frac{8.99 \times 10^9\text{ N}\cdot\text{m}^2/\text{C}^2}{0.707\text{ m}} \cdot (-2\text{ C})$$
$$V_{total} = (1.271 \times 10^{10}) \cdot (-2)$$
$$V_{total} \approx -2.54 \times 10^{10}\text{ V}$$

*Alternatively, using the exact value $r = 1/\sqrt{2}$:*
$$V_{total} = -2\sqrt{2}k \approx -2 \cdot 1.414 \cdot 8.99 \times 10^9$$
**$$V_{total} \approx -2.54 \times 10^{10}\text{ V}$$**

## 5. Conclusion
The total electric potential at the center of the square is:
**$$V \approx -2.54 \times 10^{10}\text{ Volts}$$**

> **Conceptual Tip:** Unlike the previous "Electric Force" problem where the symmetry resulted in a zero net force, the potential here is non-zero. This is because potential does not have a direction; the negative charges simply "add up" their negative potential with the positive ones, and in this case, the negative charges are stronger.