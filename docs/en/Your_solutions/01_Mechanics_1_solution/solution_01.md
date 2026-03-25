## 1. Projectile Motion — Solution

**Given:**
- Initial velocity: $v_0 = 100$ m/s
- Launch angle: $\theta = 37°$
- No air resistance, $g = 10$ m/s²

---

### Initial Velocity Components

$$v_{0x} = v_0 \cos(37°) = 100 \times 0.8 = 80 \text{ m/s}$$

$$v_{0y} = v_0 \sin(37°) = 100 \times 0.6 = 60 \text{ m/s}$$

---

### Differential Equations of Motion

**Horizontal direction** — no force acts horizontally, so acceleration = 0:

$$\frac{d^2x}{dt^2} = 0$$

Integrating once gives velocity, integrating again gives position:

$$\frac{dx}{dt} = v_{0x} = 80 \text{ m/s}$$

$$x(t) = v_{0x} \cdot t = 80t$$

**Vertical direction** — only gravity acts downward:

$$\frac{d^2y}{dt^2} = -g = -10 \text{ m/s}^2$$

Integrating once gives velocity, integrating again gives position:

$$\frac{dy}{dt} = v_{0y} - gt = 60 - 10t$$

$$y(t) = v_{0y} \cdot t - \frac{1}{2}g t^2 = 60t - 5t^2$$

---

### Time of Flight

The projectile lands when $y(t) = 0$:

$$60t - 5t^2 = 0$$

$$t(60 - 5t) = 0$$

$$t = 0 \quad \text{(launch)} \qquad \text{or} \qquad t = \frac{60}{5}$$

$$\boxed{t_{flight} = 12 \text{ s}}$$

---

### Maximum Height

Maximum height occurs when vertical velocity = 0:

$$60 - 10t = 0 \implies t_{top} = 6 \text{ s}$$

Substitute into $y(t)$:

$$H = 60(6) - 5(6)^2 = 360 - 180$$

$$\boxed{H_{max} = 180 \text{ m}}$$

---

### Range

Substitute $t_{flight} = 12$ s into $x(t)$:

$$R = 80 \times 12$$

$$\boxed{R = 960 \text{ m}}$$

---

### Summary

| Quantity | Value |
|---|---|
| Time of flight | $12$ s |
| Maximum height | $180$ m |
| Range | $960$ m |