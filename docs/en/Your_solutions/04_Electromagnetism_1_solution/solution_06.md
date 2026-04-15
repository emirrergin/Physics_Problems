### 6. Comprehensive Field Analysis: System of Discrete Charges

**Objective:** To derive the general electric field vector for a two-charge system, identify equilibrium points, and analyze the far-field behavior.

---

#### **1. System Configuration & Geometry**
We have two point charges on the x-axis:
* **Charge 1 ($q_1$):** $+q$ located at position vector $\vec{r}_1 = (-a, 0)$
* **Charge 2 ($q_2$):** $+2q$ located at position vector $\vec{r}_2 = (a, 0)$
* **Target Point ($P$):** A general point in space at $(x, y)$

**Displacement Vectors ($\vec{R} = \vec{r}_P - \vec{r}_{charge}$):**
* $\vec{R}_1 = (x - (-a))\hat{i} + (y - 0)\hat{j} = (x+a)\hat{i} + y\hat{j}$
* $\vec{R}_2 = (x - a)\hat{i} + (y - 0)\hat{j} = (x-a)\hat{i} + y\hat{j}$

**Magnitudes:**
* $R_1 = [(x+a)^2 + y^2]^{1/2}$
* $R_2 = [(x-a)^2 + y^2]^{1/2}$

---

#### **2. General Vector Derivation: $\vec{E}(x, y)$**
Applying the **Principle of Superposition**:
$$\vec{E}_{total} = \vec{E}_1 + \vec{E}_2 = k \left[ \frac{q_1}{R_1^3}\vec{R}_1 + \frac{q_2}{R_2^3}\vec{R}_2 \right]$$

Substituting the specific values for our system:
$$\vec{E}(x, y) = kq \left[ \frac{(x+a)\hat{i} + y\hat{j}}{((x+a)^2 + y^2)^{3/2}} + \frac{2((x-a)\hat{i} + y\hat{j})}{((x-a)^2 + y^2)^{3/2}} \right]$$

---

#### **3. Special Case: Field on the y-axis, $\vec{E}(0, y)$**
At $x=0$, the distances are equal ($R_1 = R_2 = R = \sqrt{a^2 + y^2}$):
$$\vec{E}(0, y) = \frac{kq}{R^3} \left[ (a\hat{i} + y\hat{j}) + 2(-a\hat{i} + y\hat{j}) \right]$$
$$\vec{E}(0, y) = \frac{kq}{(a^2 + y^2)^{3/2}} \left[ (a - 2a)\hat{i} + (y + 2y)\hat{j} \right]$$
$$\mathbf{\vec{E}(0, y) = \frac{kq}{(a^2 + y^2)^{3/2}} (-a\hat{i} + 3y\hat{j})}$$

---

#### **4. Electrostatic Equilibrium Condition ($\vec{E} = 0$)**
For the field to vanish, the net force on a test charge must be zero.
1. **Vertical Symmetry:** $E_y = 0$ only if $y = 0$ (The point must lie on the x-axis).
2. **Horizontal Balance:** Setting $E_x = 0$ on the x-axis ($y=0$) between the charges:
   $$\frac{q}{(x+a)^2} - \frac{2q}{(a-x)^2} = 0 \implies (a-x)^2 = 2(x+a)^2$$
   Take the square root of both sides:
   $$a - x = \sqrt{2}(x + a) \implies a - \sqrt{2}a = \sqrt{2}x + x$$
   $$x = a \frac{1 - \sqrt{2}}{1 + \sqrt{2}} \approx -0.17a$$
**Conclusion:** The equilibrium point is approximately $17\%$ of the distance $a$ to the left of the origin.

---

#### **5. Numerical Calculation**
**Inputs:** $a = 0.2 \text{ m}, y = 0.3 \text{ m}, q = 2 \times 10^{-6} \text{ C}$
* **Distance Constant:** $R^2 = a^2 + y^2 = (0.2)^2 + (0.3)^2 = 0.13$
* **$R^3$ factor:** $(0.13)^{1.5} \approx 0.04687$
* **Scalar Multiplier:** $\frac{kq}{R^3} = \frac{(8.99 \times 10^9)(2 \times 10^{-6})}{0.04687} \approx 383,614$

**Vector Components:**
* $E_x = 383,614 \times (-0.2) \approx -7.67 \times 10^4 \text{ N/C}$
* $E_y = 383,614 \times (3 \times 0.3) \approx 3.45 \times 10^5 \text{ N/C}$

**Final Vector:** $\mathbf{\vec{E} \approx (-7.67 \times 10^4 \hat{i} + 3.45 \times 10^5 \hat{j}) \text{ N/C}}$

---

#### **6. Far-field Limit Investigation ($y \gg a$)**
Using binomial expansion for the denominator $(a^2 + y^2)^{-3/2} \approx y^{-3}$ when $y \gg a$:
$$\vec{E}(0, y) \approx \frac{kq}{y^3} (-a\hat{i} + 3y\hat{j})$$
Since $3y \gg a$, the term $-a\hat{i}$ becomes negligible:
$$\mathbf{\vec{E}_{limit} \approx \frac{3kq}{y^2} \hat{j}}$$
**Physical Meaning:** At large distances, the system acts like a single point charge with total charge $Q = +3q$ located at the origin.