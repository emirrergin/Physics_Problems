## Dynamics with Friction Analysis

**Problem Statement:**
A $5 \text{ kg}$ block is placed on a $10 \text{ kg}$ block. A horizontal force of $45 \text{ N}$ is applied to the $10 \text{ kg}$ block, and the $5 \text{ kg}$ block is tied to the wall. The coefficient of kinetic friction between all moving surfaces is $0.2$. Find the acceleration of the $10 \text{ kg}$ block.

---

### Step 1: Identify Given Information
* **Mass of top block ($m_1$):** $5 \text{ kg}$
* **Mass of bottom block ($m_2$):** $10 \text{ kg}$
* **Applied force ($F_{app}$):** $45 \text{ N}$
* **Coefficient of kinetic friction ($\mu_k$):** $0.2$
* **Acceleration due to gravity ($g$):** $\approx 9.8 \text{ m/s}^2$
* Since the $5 \text{ kg}$ block is tied to the wall, it remains stationary relative to the ground while the $10 \text{ kg}$ block slides underneath it.

---

### Step 2: Analyze Forces Acting on the $10 \text{ kg}$ Block ($m_2$)
The $10 \text{ kg}$ block experiences the applied force pulling it forward, and two frictional forces opposing its motion:
1.  **Friction from the top block ($f_{k1}$):** Because the top block is stationary while the bottom block moves forward, the top block drags on the bottom block, exerting a frictional force in the opposite direction of the movement.
2.  **Friction from the floor ($f_{k2}$):** The floor also drags on the bottom block, opposing its motion.

---

### Step 3: Calculate the Frictional Forces
**1. Friction between the two blocks ($f_{k1}$):**
The normal force here ($N_1$) is equal to the weight of the top block.
$$N_1 = m_1 \cdot g$$
$$N_1 = 5 \cdot 9.8 = 49 \text{ N}$$
$$f_{k1} = \mu_k \cdot N_1$$
$$f_{k1} = 0.2 \cdot 49 = 9.8 \text{ N}$$

**2. Friction between the bottom block and the floor ($f_{k2}$):**
The normal force here ($N_2$) must support the weight of *both* blocks pressing down on the floor.
$$N_2 = (m_1 + m_2) \cdot g$$
$$N_2 = (5 + 10) \cdot 9.8 = 15 \cdot 9.8 = 147 \text{ N}$$
$$f_{k2} = \mu_k \cdot N_2$$
$$f_{k2} = 0.2 \cdot 147 = 29.4 \text{ N}$$

---

### Step 4: Apply Newton's Second Law
Calculate the net force ($\Sigma F$) acting on the $10 \text{ kg}$ block and use $\Sigma F = m_2 \cdot a$ to find the acceleration ($a$).

$$\Sigma F = F_{app} - f_{k1} - f_{k2}$$
$$\Sigma F = 45 - 9.8 - 29.4$$
$$\Sigma F = 45 - 39.2 = 5.8 \text{ N}$$

Now, solve for acceleration:
$$5.8 = m_2 \cdot a$$
$$5.8 = 10 \cdot a$$
$$a = \frac{5.8}{10}$$
$$a = 0.58 \text{ m/s}^2$$

**Result:**
The acceleration of the $10 \text{ kg}$ block is **$0.58 \text{ m/s}^2$**.

*(Note: In many basic physics classes, $g$ is approximated as $10 \text{ m/s}^2$ to simplify calculations without a calculator. If you use $g = 10 \text{ m/s}^2$, the friction forces become exactly $10 \text{ N}$ and $30 \text{ N}$, resulting in a net force of $5 \text{ N}$ and an acceleration of exactly **$0.5 \text{ m/s}^2$**.)*