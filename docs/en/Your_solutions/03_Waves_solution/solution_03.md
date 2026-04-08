### Question 3: Superposition Principle

**1. Identify Given Wave Equations:**
* Wave 1 (traveling to the right): $y_1(x, t) = A \sin(kx - \omega t)$
* Wave 2 (traveling to the left): $y_2(x, t) = A \sin(kx + \omega t)$

**2. Physical Principle (Superposition):**
When two waves travel through the same medium at the same time, the resulting displacement is the algebraic sum of the individual displacements:
$$y_{net}(x, t) = y_1(x, t) + y_2(x, t)$$

**3. Mathematical Tool (Trigonometric Identity):**
To solve this, we use the sum-to-product identity:
$$\sin(\alpha) + \sin(\beta) = 2 \sin\left(\frac{\alpha + \beta}{2}\right) \cos\left(\frac{\alpha - \beta}{2}\right)$$

---

**Step-by-Step Calculation for the Resulting Wave:**

* **Step 1: Set up the sum**
    $$y_{net} = A [\sin(kx - \omega t) + \sin(kx + \omega t)]$$

* **Step 2: Apply the identity**
    Let $\alpha = (kx - \omega t)$ and $\beta = (kx + \omega t)$.
    * Argument 1: $\frac{\alpha + \beta}{2} = \frac{(kx - \omega t) + (kx + \omega t)}{2} = \frac{2kx}{2} = kx$
    * Argument 2: $\frac{\alpha - \beta}{2} = \frac{(kx - \omega t) - (kx + \omega t)}{2} = \frac{-2\omega t}{2} = -\omega t$

* **Step 3: Combine terms**
    $$y_{net} = 2A \sin(kx) \cos(-\omega t)$$
    *Since $\cos(-\theta) = \cos(\theta)$, we simplify to:*
    $$\mathbf{y_{result}(x, t) = [2A \sin(kx)] \cos(\omega t)}$$

---

**Step-by-Step Calculation for Node Positions:**

**1. Define "Node":**
A node is a position where the amplitude of the standing wave is **always zero**, regardless of the time ($t$). Looking at our equation, the amplitude part is $2A \sin(kx)$. For this to be zero:
$$\sin(kx) = 0$$

**2. Find the condition for $x$:**
The sine function is zero at integer multiples of $\pi$:
$$kx = n\pi \quad \text{where } n = 0, 1, 2, 3, ...$$

**3. Solve for position ($x$):**
Recall that the wave number $k$ is defined as $k = \frac{2\pi}{\lambda}$.
$$\left(\frac{2\pi}{\lambda}\right)x = n\pi$$

Divide both sides by $\pi$:
$$\frac{2}{\lambda}x = n$$
$$x = n \cdot \frac{\lambda}{2}$$

**Final Result:**
* **Equation:** $y(x, t) = 2A \sin(kx) \cos(\omega t)$
* **Node Positions:** $\mathbf{x = 0, \frac{\lambda}{2}, \lambda, \frac{3\lambda}{2}, ...}$ (or $x = \frac{n\pi}{k}$)