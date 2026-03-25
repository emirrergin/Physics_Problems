## 2. Range Optimization — Solution

The range formula for projectile motion:

$$R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}$$

---

### Step 1: Take the Derivative

To find the maximum, differentiate $R(\theta)$ with respect to $\theta$:

$$\frac{dR}{d\theta} = \frac{v_0^2}{g} \cdot 2\cos(2\theta)$$

---

### Step 2: Set the Derivative to Zero

$$\frac{v_0^2}{g} \cdot 2\cos(2\theta) = 0$$

Since $\dfrac{2v_0^2}{g} \neq 0$, we need:

$$\cos(2\theta) = 0$$

---

### Step 3: Solve for $\theta$

$$2\theta = 90° \implies \boxed{\theta = 45°}$$

---

### Step 4: Confirm It Is a Maximum

Take the second derivative:

$$\frac{d^2R}{d\theta^2} = \frac{v_0^2}{g} \cdot (-4\sin(2\theta))$$

At $\theta = 45°$:

$$\frac{d^2R}{d\theta^2} = \frac{-4v_0^2}{g} \sin(90°) = \frac{-4v_0^2}{g} < 0$$

Since the second derivative is **negative**, this is confirmed as a **maximum**.

---

### Step 5: Maximum Range

Substitute $\theta = 45°$ back into $R(\theta)$:

$$R_{max} = \frac{v_0^2 \sin(90°)}{g} = \frac{v_0^2 \times 1}{g}$$

$$\boxed{R_{max} = \frac{v_0^2}{g}}$$

---

### Summary

| | Value |
|---|---|
| Optimal angle | $\theta = 45°$ |
| Maximum range | $R_{max} = \dfrac{v_0^2}{g}$ |

The range is maximized at **45°** because that is the angle where
$\sin(2\theta)$ reaches its peak value of **1**.