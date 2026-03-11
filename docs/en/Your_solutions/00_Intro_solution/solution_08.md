## 8. Definite Integrals — Solution

Calculate the area under $f(x) = \sin(x)$ from $x = 0$ to $x = \pi$:

$$A = \int_0^{\pi} \sin(x)\, dx$$

---

### Step 1: Find the Antiderivative

$$\int \sin(x)\, dx = -\cos(x) + C$$

---

### Step 2: Apply the Limits

$$A = \Big[-\cos(x)\Big]_0^{\pi}$$

$$A = (-\cos(\pi)) - (-\cos(0))$$

---

### Step 3: Evaluate

$$\cos(\pi) = -1, \quad \cos(0) = 1$$

$$A = (-(-1)) - (-(1))$$

$$A = 1 + 1$$

$$\boxed{A = 2}$$

---

### Geometric Interpretation

On the interval $[0, \pi]$, the function $\sin(x) \geq 0$ everywhere,
so the integral directly gives the **area** between the curve and the x-axis
without any sign issues.

| | Value |
|---|---|
| Interval | $[0,\ \pi]$ |
| Antiderivative | $-\cos(x)$ |
| Area | $2$ square units |