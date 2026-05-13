# ⚡ Physics Basics: Transformer Currents and Voltages

## 1. Problem Statement
we are analyzing an ideal transformer with the following specifications:
*   **Primary Turns ($N_p$):** $1000$ turns
*   **Secondary Turns ($N_s$):** $200$ turns
*   **Primary Voltage ($V_p$):** $120 \, \text{V (AC)}$
*   **Secondary Current ($I_s$):** $3 \, \text{A}$

**Tasks:**
1. Determine the **secondary voltage** ($V_s$).
2. Determine the **primary current** ($I_p$).

---

## 2. Fundamental Physics Principles



### A. The Transformer Equation (Voltage)
The ratio of the secondary voltage to the primary voltage is equal to the ratio of the number of turns in each coil.
$$\frac{V_s}{V_p} = \frac{N_s}{N_p}$$

### B. Conservation of Power (Current)
In an ideal transformer, power in equals power out ($P_p = P_s$). This means that voltage and current are inversely proportional to the turns ratio:
$$V_p \cdot I_p = V_s \cdot I_s \implies \frac{I_p}{I_s} = \frac{N_s}{N_p}$$

> **Note:** If the voltage is stepped down, the current is stepped up, and vice versa.

---

## 3. Step-by-Step Calculation

### Step 1: Calculate Secondary Voltage ($V_s$)
Using the voltage ratio formula:
$$V_s = V_p \cdot \left( \frac{N_s}{N_p} \right)$$
$$V_s = 120 \, \text{V} \cdot \left( \frac{200}{1000} \right)$$
$$V_s = 120 \cdot 0.2$$
**$V_s = 24 \, \text{V}$**
*This is a **Step-Down** transformer because the voltage decreased.*

---

### Step 2: Calculate Primary Current ($I_p$)
Using the current ratio formula (inverse of turns ratio):
$$I_p = I_s \cdot \left( \frac{N_s}{N_p} \right)$$
$$I_p = 3 \, \text{A} \cdot \left( \frac{200}{1000} \right)$$
$$I_p = 3 \cdot 0.2$$
**$I_p = 0.6 \, \text{A}$**

---

## 4. Final Results Summary
| Parameter | Symbol | Value | Unit |
| :--- | :---: | :--- | :--- |
| **Turns Ratio** | $N_s/N_p$ | $0.2$ | - |
| **Secondary Voltage** | $V_s$ | $24$ | $\text{V}$ |
| **Primary Current** | $I_p$ | $0.6$ | $\text{A}$ |

---

