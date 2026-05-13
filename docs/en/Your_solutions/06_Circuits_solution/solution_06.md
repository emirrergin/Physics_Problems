# ⚡ Physics Basics: Ammeter Current Analysis

## 1. Problem Statement
we need to calculate the current flowing through the ammeter located in the middle branch.

**Circuit Parameters:**
*   **Top Branch:** Source $\mathcal{E}_2 = 4.5 \, \text{V}$ and internal resistance $r_w = 1 \, \Omega$.
*   **Middle Branch:** Ammeter and resistor $R_2 = 20 \, \Omega$.
*   **Bottom Branch:** Source $\mathcal{E}_1 = 9 \, \text{V}$, internal resistance $r_w = 1 \, \Omega$, and resistor $R_1 = 10 \, \Omega$.

---

## 2. Fundamental Physics Principles
To find the current through a specific branch in a multi-loop circuit, we use **Kirchhoff’s Laws**:
*   **Kirchhoff’s Current Law (KCL):** The algebraic sum of currents at any junction (node) is zero ($\sum I = 0$).
*   **Ohm's Law:** The current between two points is the voltage difference divided by the resistance ($I = V/R$).

---

## 3. Step-by-Step Solution (Nodal Analysis)

We define the left junction as our **Reference Node (0 V)** and the right junction as **Node $V_R$**.

### Step 1: Set up the Junction Equation
According to KCL, the sum of currents leaving Node $V_R$ through the three branches must be zero:

1.  **Top Branch Current:** $\frac{V_R - 4.5}{1}$
2.  **Middle (Ammeter) Branch Current:** $\frac{V_R - 0}{20}$
3.  **Bottom Branch Current:** $\frac{V_R - (-9)}{1 + 10} = \frac{V_R + 9}{11}$ (Note: The $9\text{V}$ source is reversed relative to the node).

**Equation:**
$$\frac{V_R - 4.5}{1} + \frac{V_R}{20} + \frac{V_R + 9}{11} = 0$$

### Step 2: Solve for $V_R$
Multiplying by the common denominator (220):
$$220(V_R - 4.5) + 11V_R + 20(V_R + 9) = 0$$
$$220V_R - 990 + 11V_R + 20V_R + 180 = 0$$
$$251V_R = 810 \implies V_R \approx 3.227 \, \text{V}$$

### Step 3: Calculate Ammeter Current ($I_A$)
The ammeter current is the current through the $20 \, \Omega$ resistor:
$$I_A = \frac{V_R}{20}$$
$$I_A = \frac{3.227}{20} \approx 0.161 \, \text{A}$$

---

## 4. Final Result
The current flowing through the ammeter in  is approximately **$0.161 \, \text{A}$** (or $161 \, \text{mA}$).

---
