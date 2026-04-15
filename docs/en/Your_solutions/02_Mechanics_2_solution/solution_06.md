# 🎾 Question 6: Energy Dissipation Analysis

### 1. Problem Definition
A tennis ball is dropped from an initial height ($h_0$) of **2.0 m**. After each collision with the floor, the system undergoes a **30% energy loss**. We need to determine the maximum height ($h_2$) reached after the second bounce.

---

### 2. Physical Principles & Assumptions
* **Potential Energy ($U_g$):** Defined as $U_g = mgh$. 
* **Proportionality:** Since $m$ and $g$ are constant, $E \propto h$. An energy loss of 30% translates to a height reduction of 30%.
* **Retention Factor ($r$):** The portion of energy/height preserved is $100\% - 30\% = 70\%$ ($0.70$).
* **Inelastic Collision:** The energy loss is due to work done during the deformation of the ball, dissipating as **heat** and **sound**.

---

### 3. Step-by-Step Mathematical Solution

#### **Step 1: First Bounce ($h_1$)**
The ball retains 70% of its initial potential energy:
$$h_1 = h_0 \times 0.70$$
$$h_1 = 2.0 \text{ m} \times 0.70 = 1.4 \text{ m}$$

#### **Step 2: Second Bounce ($h_2$)**
The ball retains 70% of the energy it had at $h_1$:
$$h_2 = h_1 \times 0.70$$
$$h_2 = 1.4 \text{ m} \times 0.70 = 0.98 \text{ m}$$

#### **Verification via General Formula:**
For $n$ bounces:
$$h_n = h_0 \cdot r^n$$
$$h_2 = 2.0 \cdot (0.70)^2 = 2.0 \cdot 0.49 = \mathbf{0.98 \text{ m}}$$

---

### 4. Final Conclusion
After the second bounce, the tennis ball rises to a height of **0.98 meters**. This exponential decrease continues until the mechanical energy is fully dissipated.