### Question 4: Vector Calculus

**1. Identification of Given Physical Parameters:**
* **Position Vector ($\vec{r}(t)$):** Describes the object's location in 2D space as a function of time $t$.
  $$\vec{r}(t) = (3t^2)\hat{i} + (5t - 8t^2)\hat{j}$$
* **Goal:** Determine the object's **velocity vector** ($\vec{v}(t)$) and **acceleration vector** ($\vec{a}(t)$).

**2. Theoretical Framework & Principles:**
In kinematics, the relationship between position, velocity, and acceleration is defined by calculus:
* **Velocity ($\vec{v}$):** The first time derivative of the position vector. It represents the instantaneous rate of change of position.
  $$\vec{v}(t) = \frac{d\vec{r}}{dt}$$
* **Acceleration ($\vec{a}$):** The second time derivative of the position vector (or the first derivative of velocity). It represents the rate of change of velocity.
  $$\vec{a}(t) = \frac{d\vec{v}}{dt} = \frac{d^2\vec{r}}{dt^2}$$

---

**Step-by-Step Calculation:**

* **Step 1: Differentiating the Position Vector for Velocity ($\vec{v}$)**
    We apply the derivative operator $\frac{d}{dt}$ to each component ($\hat{i}$ and $\hat{j}$) independently:
    $$\vec{v}(t) = \frac{d}{dt}(3t^2)\hat{i} + \frac{d}{dt}(5t - 8t^2)\hat{j}$$
    
    * Applying the Power Rule ($\frac{d}{dt} t^n = n t^{n-1}$):
        * For the $x$-component: $\frac{d}{dt}(3t^2) = 3 \cdot (2t) = 6t$
        * For the $y$-component: $\frac{d}{dt}(5t - 8t^2) = (5 \cdot 1) - (8 \cdot 2t) = 5 - 16t$
    
    **Resulting Velocity Vector:**
    $$\mathbf{\vec{v}(t) = (6t)\hat{i} + (5 - 16t)\hat{j}}$$

---

* **Step 2: Differentiating the Velocity Vector for Acceleration ($\vec{a}$)**
    Now, we take the derivative of our velocity result with respect to time:
    $$\vec{a}(t) = \frac{d}{dt}(6t)\hat{i} + \frac{d}{dt}(5 - 16t)\hat{j}$$
    
    * Applying the Derivative Rules:
        * For the $x$-component: $\frac{d}{dt}(6t) = 6$
        * For the $y$-component: $\frac{d}{dt}(5) = 0$ (constant) and $\frac{d}{dt}(-16t) = -16$
    
    **Resulting Acceleration Vector:**
    $$\mathbf{\vec{a}(t) = (6)\hat{i} + (-16)\hat{j}}$$

---

**Final Summary:**
* **Position:** $\vec{r}(t) = 3t^2\hat{i} + (5t - 8t^2)\hat{j}$
* **Velocity:** $\vec{v}(t) = 6t\hat{i} + (5 - 16t)\hat{j}$
* **Acceleration:** $\vec{a}(t) = 6\hat{i} - 16\hat{j}$

*(Note: Because the acceleration vector is constant (contains no $t$ terms), the object is moving with constant acceleration, similar to projectile motion.)*