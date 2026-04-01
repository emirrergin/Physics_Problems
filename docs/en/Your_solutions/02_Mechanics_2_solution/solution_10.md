## Force Field and Power Analysis

**Problem Statement:**
In a certain force field, the equations of motion of a particle with mass $m = 0.5 \text{ kg}$ are as follows:
$$x = 5t^2 - t, \quad y = 2t^3, \quad z = -3t + 2$$
Find the time dependence of: the particle's velocity, momentum, acceleration, the force acting on it, and the power transferred by the field.

---

### Step 1: Position Vector ($\vec{r}$)
First, let's write the position of the particle as a vector function of time:
$$\vec{r}(t) = (5t^2 - t)\hat{i} + (2t^3)\hat{j} + (-3t + 2)\hat{k}$$

---

### Step 2: Velocity Vector ($\vec{v}$)
Velocity is the first derivative of the position vector with respect to time ($\vec{v} = \frac{d\vec{r}}{dt}$). We differentiate each component:
* $v_x = \frac{d}{dt}(5t^2 - t) = 10t - 1$
* $v_y = \frac{d}{dt}(2t^3) = 6t^2$
* $v_z = \frac{d}{dt}(-3t + 2) = -3$

**Velocity:**
$$\vec{v}(t) = (10t - 1)\hat{i} + (6t^2)\hat{j} - 3\hat{k}$$

---

### Step 3: Momentum Vector ($\vec{p}$)
Momentum is the product of mass and velocity ($\vec{p} = m\vec{v}$).
Given $m = 0.5 \text{ kg}$:
$$\vec{p}(t) = 0.5 \cdot [(10t - 1)\hat{i} + (6t^2)\hat{j} - 3\hat{k}]$$

**Momentum:**
$$\vec{p}(t) = (5t - 0.5)\hat{i} + (3t^2)\hat{j} - 1.5\hat{k}$$

---

### Step 4: Acceleration Vector ($\vec{a}$)
Acceleration is the first derivative of velocity with respect to time ($\vec{a} = \frac{d\vec{v}}{dt}$).
* $a_x = \frac{d}{dt}(10t - 1) = 10$
* $a_y = \frac{d}{dt}(6t^2) = 12t$
* $a_z = \frac{d}{dt}(-3) = 0$

**Acceleration:**
$$\vec{a}(t) = 10\hat{i} + (12t)\hat{j}$$

---

### Step 5: Force Vector ($\vec{F}$)
According to Newton's Second Law, force is the product of mass and acceleration ($\vec{F} = m\vec{a}$).
$$\vec{F}(t) = 0.5 \cdot [10\hat{i} + 12t\hat{j}]$$

**Force:**
$$\vec{F}(t) = 5\hat{i} + (6t)\hat{j}$$

---

### Step 6: Power Transferred ($P$)
Power is the dot product of the force vector and the velocity vector ($P = \vec{F} \cdot \vec{v}$).
$$\vec{F}(t) = \langle 5, 6t, 0 \rangle$$
$$\vec{v}(t) = \langle 10t - 1, 6t^2, -3 \rangle$$

Multiply corresponding components and add them together:
$$P(t) = (5)(10t - 1) + (6t)(6t^2) + (0)(-3)$$
$$P(t) = 50t - 5 + 36t^3$$

**Power:**
$$P(t) = 36t^3 + 50t - 5 \text{ Watts}$$