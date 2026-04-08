### Question 8: Traveling Wave Functions (Ultra-Detailed Breakdown)

**1. Theoretical Framework: The Linear Wave Equation**
For any function $y(x, t)$ to describe a valid traveling wave, it must satisfy the second-order partial differential equation known as the **Wave Equation**:
$$\frac{\partial^2 y}{\partial x^2} = \frac{1}{v^2} \frac{\partial^2 y}{\partial t^2}$$

* **LHS (Left Hand Side):** The second spatial derivative (curvature of the wave).
* **RHS (Right Hand Side):** $1/v^2$ times the second temporal derivative (acceleration of the string/medium particles).

---

**2. Testing Option (a): $y(x, t) = A \cos(kx^2 - \omega t)$**

* **Step 1: First and second spatial derivatives ($\partial x$)**
    * $\frac{\partial y}{\partial x} = -A \sin(kx^2 - \omega t) \cdot (2kx)$
    * $\frac{\partial^2 y}{\partial x^2} = -2kA [\cos(kx^2 - \omega t) \cdot 2kx \cdot x + \sin(kx^2 - \omega t) \cdot 1]$
    * *(Note: This involves the product rule and chain rule, resulting in a term with $x^2$.)*

* **Step 2: First and second temporal derivatives ($\partial t$)**
    * $\frac{\partial y}{\partial t} = -A \sin(kx^2 - \omega t) \cdot (-\omega) = A\omega \sin(kx^2 - \omega t)$
    * $\frac{\partial^2 y}{\partial t^2} = A\omega \cos(kx^2 - \omega t) \cdot (-\omega) = -A\omega^2 \cos(kx^2 - \omega t)$

* **Comparison:** The spatial derivative contains an extra $x$ term that doesn't exist in the temporal derivative. Therefore, the ratio is not a constant $v^2$.
* **Conclusion:** **Does NOT satisfy the wave equation.** (The phase must be linear in $x$, like $kx$, not $kx^2$).

---

**3. Testing Option (b): $y(x, t) = A(x - vt)^2$**

* **Step 1: Spatial derivatives ($\partial x$)**
    * $\frac{\partial y}{\partial x} = 2A(x - vt) \cdot (1) = 2A(x - vt)$
    * $\frac{\partial^2 y}{\partial x^2} = 2A$

* **Step 2: Temporal derivatives ($\partial t$)**
    * $\frac{\partial y}{\partial t} = 2A(x - vt) \cdot (-v) = -2Av(x - vt)$
    * $\frac{\partial^2 y}{\partial t^2} = -2Av \cdot (-v) = 2Av^2$

* **Step 3: Verification with Wave Equation**
    * Substitute into $\frac{\partial^2 y}{\partial x^2} = \frac{1}{v^2} \frac{\partial^2 y}{\partial t^2}$:
    * $2A = \frac{1}{v^2} (2Av^2)$
    * $2A = 2A$ (**True**)

* **Conclusion:** **Satisfies the wave equation.** (This is a pulse traveling in the $+x$ direction).

---

**4. Testing Option (c): $y(x, t) = A \log(x + vt)$**

* **Step 1: Spatial derivatives ($\partial x$)**
    * $\frac{\partial y}{\partial x} = \frac{A}{x + vt}$
    * $\frac{\partial^2 y}{\partial x^2} = -\frac{A}{(x + vt)^2}$

* **Step 2: Temporal derivatives ($\partial t$)**
    * $\frac{\partial y}{\partial t} = \frac{A}{x + vt} \cdot (v) = \frac{Av}{x + vt}$
    * $\frac{\partial^2 y}{\partial t^2} = -\frac{Av}{(x + vt)^2} \cdot (v) = -\frac{Av^2}{(x + vt)^2}$

* **Step 3: Verification with Wave Equation**
    * Substitute into $\frac{\partial^2 y}{\partial x^2} = \frac{1}{v^2} \frac{\partial^2 y}{\partial t^2}$:
    * $-\frac{A}{(x + vt)^2} = \frac{1}{v^2} \left( -\frac{Av^2}{(x + vt)^2} \right)$
    * $-\frac{A}{(x + vt)^2} = -\frac{A}{(x + vt)^2}$ (**True**)

* **Conclusion:** **Satisfies the wave equation.** (This describes a wave traveling in the $-x$ direction).

---

**Final Summary:**
A traveling wave must be a function of the form $f(x \pm vt)$. 
* **Answer (a)** is not of this form because of the $x^2$. 
* **Answer (b)** is in the form $f(x - vt)$. 
* **Answer (c)** is in the form $f(x + vt)$.

**Correct Options: (b) and (c)**