## 1. Vector Algebra — Solution

Given vectors:

$$\vec{a} = [2, 1, -3], \quad \vec{b} = [4, -2, 1]$$

---

### a) Magnitude of Each Vector

$$|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2} = \sqrt{4 + 1 + 9} = \sqrt{14} \approx 3.742$$

$$|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2} = \sqrt{16 + 4 + 1} = \sqrt{21} \approx 4.583$$

---

### b) Dot Product $\vec{a} \cdot \vec{b}$

$$\vec{a} \cdot \vec{b} = (2)(4) + (1)(-2) + (-3)(1)$$

$$= 8 - 2 - 3 = \boxed{3}$$

---

### c) Cross Product $\vec{a} \times \vec{b}$

$$\vec{a} \times \vec{b} = \begin{vmatrix} \vec{i} & \vec{j} & \vec{k} \\ 2 & 1 & -3 \\ 4 & -2 & 1 \end{vmatrix}$$

Computing each component:

$$i: \quad (1)(1) - (-3)(-2) = 1 - 6 = -5$$

$$j: \quad -\left[(2)(1) - (-3)(4)\right] = -[2 + 12] = -14$$

$$k: \quad (2)(-2) - (1)(4) = -4 - 4 = -8$$

$$\boxed{\vec{a} \times \vec{b} = [-5,\ -14,\ -8]}$$

**Verification** — the cross product must be perpendicular to both vectors:

$$(-5)(2) + (-14)(1) + (-8)(-3) = -10 - 14 + 24 = 0 \checkmark$$

$$(-5)(4) + (-14)(-2) + (-8)(1) = -20 + 28 - 8 = 0 \checkmark$$

---

### d) Angle Between the Vectors

Using the angle formula:

$$\cos\theta = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}|\ |\vec{b}|}$$

Substituting the values:

$$\cos\theta = \frac{3}{\sqrt{14} \cdot \sqrt{21}} = \frac{3}{\sqrt{294}} = \frac{3}{17.146} \approx 0.1750$$

$$\theta = \arccos(0.1750) \approx \boxed{79.93°}$$