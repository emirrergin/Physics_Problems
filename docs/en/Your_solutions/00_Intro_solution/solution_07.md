## 7. Logic & Series — Solution

**Given:**
- Distance between bicycle and wall: $d = 10$ m
- Bicycle speed: $v_b = 1$ m/s
- Fly speed: $v_f = 2$ m/s

---

### Key Insight

Instead of summing an infinite series of back-and-forth trips,
we use a much more elegant approach:

> **The fly travels for exactly as long as it takes the bicycle to reach the wall.**

---

### Step 1: Find the Time Until the Bicycle Hits the Wall

The bicycle travels 10 m at 1 m/s:

$$t = \frac{d}{v_b} = \frac{10}{1} = 10 \text{ s}$$

---

### Step 2: Find the Total Distance the Fly Travels

The fly moves continuously at 2 m/s for the entire duration $t = 10$ s:

$$D = v_f \times t = 2 \times 10$$

$$\boxed{D = 20 \text{ m}}$$

---

### Why Not an Infinite Series?

The long way would be to sum each leg of the fly's journey:

$$D = \sum_{n=0}^{\infty} d_n$$

This forms a **geometric series** that converges to the same answer — but it is
unnecessarily complex. The elegant trick is recognizing that regardless of how
many times the fly bounces, **it always flies at 2 m/s for exactly 10 seconds**.

---

### Result

$$\boxed{D_{\text{total}} = 20 \text{ m}}$$