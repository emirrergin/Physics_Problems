## 4. Vector Calculus — Solution

**Given position vector:**

$$\vec{r}(t) = (3t^2)\hat{i} + (5t - 8t^2)\hat{j}$$

---

### Velocity Vector

Velocity is the **first derivative** of position with respect to time:

$$\vec{v}(t) = \frac{d\vec{r}}{dt}$$

Differentiate each component separately:

$$\frac{d}{dt}(3t^2) = 6t$$

$$\frac{d}{dt}(5t - 8t^2) = 5 - 16t$$

$$\boxed{\vec{v}(t) = 6t\,\hat{i} + (5 - 16t)\,\hat{j} \quad \text{(m/s)}}$$

---

### Acceleration Vector

Acceleration is the **first derivative** of velocity (or **second derivative** of position):

$$\vec{a}(t) = \frac{d\vec{v}}{dt}$$

Differentiate each component of $\vec{v}(t)$:

$$\frac{d}{dt}(6t) = 6$$

$$\frac{d}{dt}(5 - 16t) = -16$$

$$\boxed{\vec{a}(t) = 6\,\hat{i} + (-16)\,\hat{j} \quad \text{(m/s}^2\text{)}}$$

---

### Key Observation

The acceleration is **constant** — it does not change with time.
This means the object experiences a uniform force in both directions.

---

### Summary

| Quantity | Vector |
|---|---|
| Position | $\vec{r}(t) = 3t^2\,\hat{i} + (5t-8t^2)\,\hat{j}$ |
| Velocity | $\vec{v}(t) = 6t\,\hat{i} + (5-16t)\,\hat{j}$ |
| Acceleration | $\vec{a}(t) = 6\,\hat{i} - 16\,\hat{j}$ |