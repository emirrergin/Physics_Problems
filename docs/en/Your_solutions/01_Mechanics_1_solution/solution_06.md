## 6. Variable Velocity — Solution

**Given:**
- Velocity: $v(t) = t^2 + 2t - 5$
- Initial condition: $x = 4$ at $t = 0$
- Find: position and acceleration at $t = 3$

---

### Position $x(t)$

Position is the **integral** of velocity:

$$x(t) = \int v(t)\, dt = \int (t^2 + 2t - 5)\, dt$$

$$x(t) = \frac{t^3}{3} + t^2 - 5t + C$$

**Apply the initial condition** $x(0) = 4$:

$$4 = \frac{0}{3} + 0 - 0 + C \implies C = 4$$

$$\boxed{x(t) = \frac{t^3}{3} + t^2 - 5t + 4}$$

---

### Position at $t = 3$

$$x(3) = \frac{(3)^3}{3} + (3)^2 - 5(3) + 4$$

$$= \frac{27}{3} + 9 - 15 + 4$$

$$= 9 + 9 - 15 + 4$$

$$\boxed{x(3) = 7 \text{ m}}$$

---

### Acceleration $a(t)$

Acceleration is the **derivative** of velocity:

$$a(t) = \frac{dv}{dt} = \frac{d}{dt}(t^2 + 2t - 5)$$

$$\boxed{a(t) = 2t + 2}$$

---

### Acceleration at $t = 3$

$$a(3) = 2(3) + 2 = 6 + 2$$

$$\boxed{a(3) = 8 \text{ m/s}^2}$$

---

### Summary

| Quantity | Value at $t = 3$ |
|---|---|
| Position | $x(3) = 7$ m |
| Velocity | $v(3) = 9 + 6 - 5 = 10$ m/s |
| Acceleration | $a(3) = 8$ m/s² |