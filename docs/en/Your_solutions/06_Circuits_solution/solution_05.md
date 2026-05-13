# ⚡ Physics Basics: Kirchhoff's Laws (Multi-Loop Circuit)

## 1. Problem Statement
Based on **image_1cb980.png**, we need to find the currents $I_1, I_2$, and $I_3$ in the given two-loop circuit.
*   **Left Branch:** Source $\mathcal{E}_1 = 4.5 \, \text{V}$ and internal resistance $r_w = 1 \, \Omega$.
*   **Top Branch (Left Loop):** Resistor $R_1 = 20 \, \Omega$ and Ammeter $A$.
*   **Shared Middle Branch:** Resistor $R_2 = 10 \, \Omega$.
*   **Right Branch:** Source $\mathcal{E}_2 = 9 \, \text{V}$ and internal resistance $r_w = 1 \, \Omega$.

---

## 2. Fundamental Physics Principles
To analyze multi-loop circuits, we use two fundamental laws:
*   **Kirchhoff's Junction Rule (KCL):** The sum of currents entering a junction equals the sum of currents leaving it ($\sum I_{in} = \sum I_{out}$).
*   **Kirchhoff's Loop Rule (KVL):** The algebraic sum of changes in potential around any closed circuit loop must be zero ($\sum \Delta V = 0$).




---

## 3. Step-by-Step Solution

### Step 1: Define Current Directions and Junction Equation
Let's assume the following directions:
*   $I_1$: Flows clockwise in the left loop (up through the left branch, right through $R_1$).
*   $I_3$: Flows counter-clockwise in the right loop (up through the right branch).
*   $I_2$: Flows downwards through the shared middle resistor $R_2$.

At the top junction:
$$I_1 + I_3 = I_2 \implies I_3 = I_2 - I_1$$

### Step 2: Apply Loop Rule (KVL)
**Left Loop (Clockwise):**
Starting from the bottom left corner:
$$\mathcal{E}_1 - I_1 \cdot r_w - I_1 \cdot R_1 - I_2 \cdot R_2 = 0$$
$$4.5 - 1I_1 - 20I_1 - 10I_2 = 0$$
$$21I_1 + 10I_2 = 4.5 \quad \text{--- (Eq. 1)}$$

**Right Loop (Counter-Clockwise):**
Starting from the bottom right corner:
$$\mathcal{E}_2 - I_3 \cdot r_w - I_2 \cdot R_2 = 0$$
$$9 - 1I_3 - 10I_2 = 0$$
$$I_3 + 10I_2 = 9 \quad \text{--- (Eq. 2)}$$

### Step 3: Solve the System of Equations
Substitute $I_3 = I_2 - I_1$ into **Eq. 2**:
$$(I_2 - I_1) + 10I_2 = 9 \implies 11I_2 - I_1 = 9 \implies I_1 = 11I_2 - 9$$

Now, substitute this expression for $I_1$ into **Eq. 1**:
$$21(11I_2 - 9) + 10I_2 = 4.5$$
$$231I_2 - 189 + 10I_2 = 4.5$$
$$241I_2 = 193.5 \implies I_2 \approx 0.803 \, \text{A}$$

Next, solve for $I_1$:
$$I_1 = 11(0.803) - 9 = 8.833 - 9 \approx -0.167 \, \text{A}$$

Finally, solve for $I_3$:
$$I_3 = 0.803 - (-0.167) \approx 0.970 \, \text{A}$$

---

## 4. Final Results
*   **$I_1 \approx -0.167 \, \text{A}$** (The negative sign means the current actually flows counter-clockwise).
*   **$I_2 \approx 0.803 \, \text{A}$**
*   **$I_3 \approx 0.970 \, \text{A}$**

---
