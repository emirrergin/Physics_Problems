## Dynamics with a Time-Dependent Force Analysis

**Problem Statement:**
A particle of mass $m = 3 \text{ kg}$ moves in a force field $F$ dependent on time in the following way:
$$F = (15t, 3t - 12, -6t^2) \text{ N}$$
Assuming initial conditions $r_0 = (5, 2, -3) \text{ m}$ and $v_0 = (2, 0, 1) \text{ m/s}$, find the dependence of the particle's position and velocity on time.

---

### Step 1: Find the Acceleration Vector ($a(t)$)
According to Newton's Second Law, $\vec{F} = m\vec{a}$. We can find the acceleration by dividing the force vector by the mass ($m = 3 \text{ kg}$).

$$a(t) = \frac{1}{m} F(t)$$
$$a(t) = \frac{1}{3} (15t, 3t - 12, -6t^2)$$
$$a(t) = \left(\frac{15t}{3}, \frac{3t - 12}{3}, \frac{-6t^2}{3}\right)$$

**Acceleration:**
$$a(t) = (5t, t - 4, -2t^2) \text{ m/s}^2$$

---

### Step 2: Find the Velocity Vector ($v(t)$)
Velocity is the integral of acceleration with respect to time: $v(t) = \int a(t) dt$. We integrate each component and add a constant of integration vector $\vec{C_1}$.

$$v(t) = \int (5t, t - 4, -2t^2) dt$$
$$v(t) = \left( \int 5t dt, \int (t - 4) dt, \int -2t^2 dt \right)$$
$$v(t) = \left( \frac{5}{2}t^2 + C_{1x}, \frac{1}{2}t^2 - 4t + C_{1y}, -\frac{2}{3}t^3 + C_{1z} \right)$$

To find the constants, we use the initial velocity condition $v_0 = v(0) = (2, 0, 1)$:
$$v(0) = \left( \frac{5}{2}(0)^2 + C_{1x}, \frac{1}{2}(0)^2 - 4(0) + C_{1y}, -\frac{2}{3}(0)^3 + C_{1z} \right) = (2, 0, 1)$$
$$(C_{1x}, C_{1y}, C_{1z}) = (2, 0, 1)$$

Substitute the constants back into the velocity equation:
**Velocity:**
$$v(t) = \left( \frac{5}{2}t^2 + 2, \frac{1}{2}t^2 - 4t, -\frac{2}{3}t^3 + 1 \right) \text{ m/s}$$

---

### Step 3: Find the Position Vector ($r(t)$)
Position is the integral of velocity with respect to time: $r(t) = \int v(t) dt$. We integrate each component and add a new constant of integration vector $\vec{C_2}$.

$$r(t) = \int \left( \frac{5}{2}t^2 + 2, \frac{1}{2}t^2 - 4t, -\frac{2}{3}t^3 + 1 \right) dt$$
$$r(t) = \left( \int \left(\frac{5}{2}t^2 + 2\right) dt, \int \left(\frac{1}{2}t^2 - 4t\right) dt, \int \left(-\frac{2}{3}t^3 + 1\right) dt \right)$$
$$r(t) = \left( \frac{5}{6}t^3 + 2t + C_{2x}, \frac{1}{6}t^3 - 2t^2 + C_{2y}, -\frac{2}{12}t^4 + t + C_{2z} \right)$$
$$r(t) = \left( \frac{5}{6}t^3 + 2t + C_{2x}, \frac{1}{6}t^3 - 2t^2 + C_{2y}, -\frac{1}{6}t^4 + t + C_{2z} \right)$$

To find the constants, we use the initial position condition $r_0 = r(0) = (5, 2, -3)$:
$$r(0) = \left( \frac{5}{6}(0)^3 + 2(0) + C_{2x}, \frac{1}{6}(0)^3 - 2(0)^2 + C_{2y}, -\frac{1}{6}(0)^4 + (0) + C_{2z} \right) = (5, 2, -3)$$
$$(C_{2x}, C_{2y}, C_{2z}) = (5, 2, -3)$$

Substitute the constants back into the position equation:
**Position:**
$$r(t) = \left( \frac{5}{6}t^3 + 2t + 5, \frac{1}{6}t^3 - 2t^2 + 2, -\frac{1}{6}t^4 + t - 3 \right) \text{ m}$$