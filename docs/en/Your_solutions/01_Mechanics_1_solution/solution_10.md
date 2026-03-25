## 10. Kinematics — Solution

**Given:**

$$\vec{r}(t) = (a\cos(\omega t),\ b\sin(\omega t),\ bt)$$

---

### a) Equation of the Trajectory

From the x and y components:

$$x = a\cos(\omega t) \implies \cos(\omega t) = \frac{x}{a}$$

$$y = b\sin(\omega t) \implies \sin(\omega t) = \frac{y}{b}$$

Apply the identity $\sin^2 + \cos^2 = 1$:

$$\left(\frac{x}{a}\right)^2 + \left(\frac{y}{b}\right)^2 = 1$$

From the z component:

$$z = bt \implies t = \frac{z}{b}$$

So the full trajectory equation is:

$$\boxed{\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1, \qquad z = bt}$$

This is a **helix on an elliptical cylinder** — the point winds around
an ellipse while rising linearly in z.

---

### b) Path Length from $t = 0$ to $t = t_0$

First find the velocity vector:

$$\vec{v}(t) = \frac{d\vec{r}}{dt} = (-a\omega\sin(\omega t),\ b\omega\cos(\omega t),\ b)$$

Speed (magnitude of velocity):

$$|\vec{v}(t)| = \sqrt{a^2\omega^2\sin^2(\omega t) + b^2\omega^2\cos^2(\omega t) + b^2}$$

**General case** ($a \neq b$): the integral has no simple closed form (elliptic integral):

$$L = \int_0^{t_0} \sqrt{\omega^2(a^2\sin^2(\omega t) + b^2\cos^2(\omega t)) + b^2}\ dt$$

**Special case** ($a = b$): the ellipse becomes a circle, speed becomes constant:

$$|\vec{v}(t)| = \sqrt{a^2\omega^2 + b^2} = \text{constant}$$

$$\boxed{L = t_0\sqrt{a^2\omega^2 + b^2}}$$

---

### c) Special Cases

| Condition | Shape |
|---|---|
| $a = b$ | Circular helix (uniform winding) |
| $a \neq b$ | Elliptical helix (non-uniform winding) |
| $\omega \to 0$ | Straight line along z-axis |
| $b \to 0$ | Flat ellipse in the xy-plane (no z rise) |
| $a \to 0$ | Straight line along z-axis (collapsed ellipse) |



![alt text](image.png)