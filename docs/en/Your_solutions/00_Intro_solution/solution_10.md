## 10. Infinite Series — Solution

The ant starts at the origin (0, 0) and moves in a repeating 4-direction cycle:

| Step | Distance | Direction |
|------|----------|-----------|
| 1 | $1$ | East (+x) |
| 2 | $1/2$ | North (+y) |
| 3 | $1/3$ | West (−x) |
| 4 | $1/4$ | South (−y) |
| 5 | $1/5$ | East (+x) |
| 6 | $1/6$ | North (+y) |
| ... | ... | ... |

---

### X Position (East and West movements)

East and West movements affect the x-axis.
East is positive (+), West is negative (−):

$$x = 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \cdots$$

This is a well-known result in mathematics called the **Leibniz formula**:

$$x = \frac{\pi}{4} \approx 0.7854 \text{ m}$$

---

### Y Position (North and South movements)

North and South movements affect the y-axis.
North is positive (+), South is negative (−):

$$y = \frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \frac{1}{8} + \cdots$$

We can factor out $\dfrac{1}{2}$:

$$y = \frac{1}{2}\left(1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \cdots\right)$$

The part inside the brackets is another well-known result called the
**alternating harmonic series**, which equals $\ln(2)$:

$$y = \frac{\ln(2)}{2} \approx 0.3466 \text{ m}$$

---

### Final Position

$$\boxed{\left(\frac{\pi}{4},\ \frac{\ln 2}{2}\right) \approx (0.785 \text{ m East},\ 0.347 \text{ m North})}$$