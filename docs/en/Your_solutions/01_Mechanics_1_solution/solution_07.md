## 7. Elimination of Time and Interpretation of Acceleration — Solution

**Given:**

$$x(t) = 2t^2, \qquad y(t) = 3t^3$$

---

### Step 1: Eliminate the Parameter $t$

From $x(t)$:

$$x = 2t^2 \implies t^2 = \frac{x}{2} \implies t = \sqrt{\frac{x}{2}}$$

Substitute into $y(t) = 3t^3 = 3t \cdot t^2$:

$$y = 3 \cdot \sqrt{\frac{x}{2}} \cdot \frac{x}{2} = \frac{3x}{2} \cdot \sqrt{\frac{x}{2}}$$

$$\boxed{y = \frac{3}{2\sqrt{2}}\, x^{3/2}}$$

This is the **path equation** (valid for $x \geq 0$).

---

### Step 2: Trajectory Shape

| $t$ | $x = 2t^2$ | $y = 3t^3$ |
|-----|-----------|-----------|
| $0$ | $0$ | $0$ |
| $1$ | $2$ | $3$ |
| $2$ | $8$ | $24$ |
| $3$ | $18$ | $81$ |

The trajectory starts at the origin and curves upward following $y \propto x^{3/2}$.
It rises steeply as $x$ increases — faster than a parabola, slower than a cubic.

---

### Step 3: Velocity Vector $\vec{v}(t)$

Differentiate position components with respect to $t$:

$$v_x = \frac{dx}{dt} = 4t$$

$$v_y = \frac{dy}{dt} = 9t^2$$

$$\boxed{\vec{v}(t) = 4t\,\hat{i} + 9t^2\,\hat{j} \quad \text{(m/s)}}$$

---

### Step 4: Speed $|\vec{v}(t)|$

$$|\vec{v}(t)| = \sqrt{v_x^2 + v_y^2} = \sqrt{(4t)^2 + (9t^2)^2}$$

$$= \sqrt{16t^2 + 81t^4} = t\sqrt{16 + 81t^2}$$

$$\boxed{|\vec{v}(t)| = t\sqrt{16 + 81t^2} \quad \text{(m/s)}}$$

---

### Step 5: Acceleration Vector $\vec{a}(t)$

Differentiate velocity components with respect to $t$:

$$a_x = \frac{dv_x}{dt} = 4$$

$$a_y = \frac{dv_y}{dt} = 18t$$

$$\boxed{\vec{a}(t) = 4\,\hat{i} + 18t\,\hat{j} \quad \text{(m/s}^2\text{)}}$$

---

### Step 6: Magnitude of Acceleration $|\vec{a}(t)|$

$$|\vec{a}(t)| = \sqrt{a_x^2 + a_y^2} = \sqrt{4^2 + (18t)^2}$$

$$\boxed{|\vec{a}(t)| = \sqrt{16 + 324t^2} \quad \text{(m/s}^2\text{)}}$$

---

### Step 7: Is the Acceleration Constant?

$$\vec{a}(t) = 4\,\hat{i} + 18t\,\hat{j}$$

The $x$-component is constant ($4$), but the $y$-component $18t$ **depends on time**.

> **No — the acceleration is NOT constant.**
> It grows over time because the $y$-component increases linearly with $t$.

---

### Summary

| Quantity | Expression |
|---|---|
| Path equation | $y = \dfrac{3}{2\sqrt{2}}\, x^{3/2}$ |
| Velocity | $\vec{v}(t) = 4t\,\hat{i} + 9t^2\,\hat{j}$ |
| Speed | $\|\vec{v}(t)\| = t\sqrt{16 + 81t^2}$ |
| Acceleration | $\vec{a}(t) = 4\,\hat{i} + 18t\,\hat{j}$ |
| Magnitude of acceleration | $\|\vec{a}(t)\| = \sqrt{16 + 324t^2}$ |
| Constant acceleration? | **No** |