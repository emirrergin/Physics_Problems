## 3. Path Intersection — Solution

**Given:**
- Alice: $A(t) = (2+t,\ 8-3t)$
- Bob: $B(t) = (2t-1,\ 2t+2)$

---

### Step 1: Check if Paths Cross (at possibly different times)

Set $A(t) = B(s)$ using different time parameters $t$ and $s$:

$$2 + t = 2s - 1 \quad \Rightarrow \quad t = 2s - 3 \tag{1}$$

$$8 - 3t = 2s + 2 \quad \Rightarrow \quad 3t + 2s = 6 \tag{2}$$

Substitute (1) into (2):

$$3(2s-3) + 2s = 6$$

$$8s - 9 = 6 \implies s = \frac{15}{8}, \quad t = \frac{3}{4}$$

**Verify the intersection point:**

$$A\!\left(\frac{3}{4}\right) = \left(\frac{11}{4},\ \frac{23}{4}\right)$$

$$B\!\left(\frac{15}{8}\right) = \left(\frac{11}{4},\ \frac{23}{4}\right) \checkmark$$

> The **paths do cross** at $\left(\dfrac{11}{4},\ \dfrac{23}{4}\right)$,
> but Alice arrives at $t = \dfrac{3}{4}$ and Bob at $t = \dfrac{15}{8}$.

---

### Step 2: Check if They Collide (same place, same time)

Set $A(t) = B(t)$ using the **same** $t$:

$$2 + t = 2t - 1 \implies t = 3 \tag{from x}$$

$$8 - 3t = 2t + 2 \implies t = \frac{6}{5} \tag{from y}$$

The two equations give **different** values of $t$, so:

> **They never collide.**

---

### Step 3: Find the Minimum Distance

The squared distance between them at time $t$:

$$D^2(t) = \bigl[(2+t)-(2t-1)\bigr]^2 + \bigl[(8-3t)-(2t+2)\bigr]^2$$

$$D^2(t) = (3-t)^2 + (6-5t)^2$$

Expand:

$$D^2(t) = 9 - 6t + t^2 + 36 - 60t + 25t^2 = 26t^2 - 66t + 45$$

---

### Step 4: Minimize $D^2(t)$

Take the derivative and set it to zero:

$$\frac{d(D^2)}{dt} = 52t - 66 = 0$$

$$\boxed{t = \frac{66}{52} = \frac{33}{26} \approx 1.269 \text{ s}}$$

---

### Step 5: Calculate the Minimum Distance

$$D^2\!\left(\frac{33}{26}\right) = 26\left(\frac{33}{26}\right)^2 - 66\left(\frac{33}{26}\right) + 45$$

$$= \frac{26 \cdot 1089}{676} - \frac{2178}{26} + 45 = \frac{81}{26}$$

$$D_{min} = \sqrt{\frac{81}{26}} = \frac{9}{\sqrt{26}} = \frac{9\sqrt{26}}{26}$$

$$\boxed{D_{min} = \frac{9\sqrt{26}}{26} \approx 1.765 \text{ m}}$$

---

### Summary

| | Result |
|---|---|
| Paths intersect? | **Yes**, at $\left(\dfrac{11}{4},\ \dfrac{23}{4}\right)$ |
| Do they collide? | **No** — they arrive at different times |
| Minimum distance | $\dfrac{9\sqrt{26}}{26} \approx 1.765$ m |
| Time of closest approach | $t = \dfrac{33}{26} \approx 1.27$ s |