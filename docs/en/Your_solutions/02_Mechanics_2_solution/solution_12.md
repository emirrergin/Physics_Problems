## Work and Energy with a Constant Force

**Given:**
* Mass $m = 2 \text{ kg}$
* Force vector $\vec{F} = \langle 6, 2 \rangle \text{ N}$
* Initial velocity $\vec{v}(0) = \langle 1, -1 \rangle \text{ m/s}$
* Initial position $\vec{r}(0) = \langle 0, 0 \rangle \text{ m}$

---

### 1. Determine the Acceleration ($\vec{a}(t)$)
Using Newton's Second Law ($\vec{F} = m\vec{a}$), we divide the constant force vector by the mass.
$$\vec{a}(t) = \frac{\vec{F}}{m}$$
$$\vec{a}(t) = \frac{\langle 6, 2 \rangle}{2}$$
**Acceleration:**
$$\vec{a}(t) = \langle 3, 1 \rangle \text{ m/s}^2$$
*(Note: Since the force is constant, the acceleration is also constant and does not depend on time $t$.)*

---

### 2. Determine the Velocity ($\vec{v}(t)$)
Velocity is the integral of acceleration with respect to time.
$$\vec{v}(t) = \int \vec{a} dt = \int \langle 3, 1 \rangle dt$$
$$\vec{v}(t) = \langle 3t + C_x, t + C_y \rangle$$

Apply the initial velocity condition $\vec{v}(0) = \langle 1, -1 \rangle$ to find the constants:
$$\vec{v}(0) = \langle 3(0) + C_x, (0) + C_y \rangle = \langle 1, -1 \rangle$$
$$C_x = 1, \quad C_y = -1$$

**Velocity:**
$$\vec{v}(t) = \langle 3t + 1, t - 1 \rangle \text{ m/s}$$

---

### 3. Determine the Position ($\vec{r}(t)$)
Position is the integral of velocity with respect to time.
$$\vec{r}(t) = \int \vec{v}(t) dt = \int \langle 3t + 1, t - 1 \rangle dt$$
$$\vec{r}(t) = \left\langle \frac{3}{2}t^2 + t + C_{2x}, \frac{1}{2}t^2 - t + C_{2y} \right\rangle$$

Apply the initial position condition $\vec{r}(0) = \langle 0, 0 \rangle$:
$$\vec{r}(0) = \langle 0 + 0 + C_{2x}, 0 - 0 + C_{2y} \rangle = \langle 0, 0 \rangle$$
$$C_{2x} = 0, \quad C_{2y} = 0$$

**Position:**
$$\vec{r}(t) = \langle 1.5t^2 + t, 0.5t^2 - t \rangle \text{ m}$$

---

### 4. Trajectory of the Motion
The trajectory is a curve in the xy-plane defined by the parametric equations:
* $x(t) = 1.5t^2 + t$
* $y(t) = 0.5t^2 - t$

If we eliminate the parameter $t$, we would find that this describes a parabola. *(See the Python code at the bottom of this document to draw the exact trajectory).*

---

### 5. Work Done by the Force at $t = 3 \text{ s}$
Since the force is constant, the work done ($W$) is the dot product of the force vector and the displacement vector ($\Delta\vec{r}$).

First, find the position at $t = 3$:
$$\vec{r}(3) = \langle 1.5(3)^2 + 3, 0.5(3)^2 - 3 \rangle$$
$$\vec{r}(3) = \langle 1.5(9) + 3, 0.5(9) - 3 \rangle$$
$$\vec{r}(3) = \langle 13.5 + 3, 4.5 - 3 \rangle$$
$$\vec{r}(3) = \langle 16.5, 1.5 \rangle \text{ m}$$

Since $\vec{r}(0) = \langle 0, 0 \rangle$, the displacement is $\Delta\vec{r} = \langle 16.5, 1.5 \rangle$.

Now calculate the work:
$$W = \vec{F} \cdot \Delta\vec{r}$$
$$W = \langle 6, 2 \rangle \cdot \langle 16.5, 1.5 \rangle$$
$$W = (6)(16.5) + (2)(1.5)$$
$$W = 99 + 3$$
**Work Done:**
$$W = 102 \text{ Joules}$$

---

### 6. Consistency with the Work-Energy Theorem
The Work-Energy Theorem states that the work done on an object equals its change in kinetic energy ($W = \Delta KE = KE_f - KE_i$).

Let's calculate the kinetic energy ($KE = \frac{1}{2}m|\vec{v}|^2$) at $t = 0$ and $t = 3$.

**Initial Kinetic Energy ($KE_i$) at $t = 0$:**
$$\vec{v}(0) = \langle 1, -1 \rangle$$
$$|\vec{v}(0)|^2 = (1)^2 + (-1)^2 = 1 + 1 = 2$$
$$KE_i = \frac{1}{2}(2 \text{ kg})(2) = 2 \text{ J}$$

**Final Kinetic Energy ($KE_f$) at $t = 3$:**
$$\vec{v}(3) = \langle 3(3) + 1, 3 - 1 \rangle = \langle 10, 2 \rangle$$
$$|\vec{v}(3)|^2 = (10)^2 + (2)^2 = 100 + 4 = 104$$
$$KE_f = \frac{1}{2}(2 \text{ kg})(104) = 104 \text{ J}$$

**Change in Kinetic Energy ($\Delta KE$):**
$$\Delta KE = KE_f - KE_i$$
$$\Delta KE = 104 - 2$$
$$\Delta KE = 102 \text{ Joules}$$

**Conclusion:** The calculated Work ($102 \text{ J}$) exactly matches the change in Kinetic Energy ($102 \text{ J}$). The results are perfectly consistent with the Work-Energy Theorem.

---

### Python Code to Draw the Trajectory
You can run this snippet to visualize the particle's path:

```python
import numpy as np
import matplotlib.pyplot as plt

# Generate time values from 0 to 3 seconds
t = np.linspace(0, 3, 100)

# Parametric equations for x and y
x = 1.5 * t**2 + t
y = 0.5 * t**2 - t

# Plotting the trajectory
plt.figure(figsize=(8, 6))
plt.plot(x, y, color='purple', label='Trajectory from t=0 to t=3')
plt.scatter(x[0], y[0], color='green', zorder=5, label='Start (t=0)')
plt.scatter(x[-1], y[-1], color='red', zorder=5, label='End (t=3)')

plt.title('Particle Trajectory')
plt.xlabel('Position X (m)')
plt.ylabel('Position Y (m)')
plt.axhline(0, color='black', linewidth=0.5)
plt.axvline(0, color='black', linewidth=0.5)
plt.grid(True, linestyle='--', alpha=0.7)
plt.legend()
plt.show()