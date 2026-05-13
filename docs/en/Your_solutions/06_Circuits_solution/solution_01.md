# 🔌 Physics Basics: Series and Parallel Circuits

## 1. Problem Statement
we have three resistors and a power source:
* **Resistors:** $R_1 = 15 \, \Omega$, $R_2 = 30 \, \Omega$, and $R_3 = 50 \, \Omega$
* **Battery Voltage ($V$):** $12 \, \text{V}$

**Task:** Calculate the total equivalent resistance ($R_{eq}$) and the total current ($I$) for both **series** and **parallel** connections.

---

## 2. Fundamental Physics Principles

### A. Ohm's Law
The relationship between voltage, current, and resistance is defined by:
$$V = I \cdot R \implies I = \frac{V}{R}$$

### B. Series Connection Logic
In a series circuit, there is only one path for the current. The total resistance is the sum of all individual resistances:
$$R_{series} = R_1 + R_2 + R_3$$

### C. Parallel Connection Logic
In a parallel circuit, the voltage across each resistor is the same, but the current splits. The reciprocal of the total resistance is the sum of the reciprocals of each resistance:
$$\frac{1}{R_{parallel}} = \frac{1}{R_1} + \frac{1}{R_2} + \frac{1}{R_3}$$

---

## 3. Case 1: Series Connection

### Step 1: Calculate Total Resistance ($R_{eq}$)
$$R_{eq} = 15 \, \Omega + 30 \, \Omega + 50 \, \Omega$$
**$R_{eq} = 95 \, \Omega$**

### Step 2: Calculate Total Current ($I$)
Using Ohm's Law:
$$I = \frac{12 \, \text{V}}{95 \, \Omega}$$
**$I \approx 0.126 \, \text{A}$** (or $126 \, \text{mA}$)

---

## 4. Case 2: Parallel Connection

### Step 1: Calculate Total Resistance ($R_{eq}$)
$$\frac{1}{R_{eq}} = \frac{1}{15} + \frac{1}{30} + \frac{1}{50}$$

To solve this, we find a common denominator (150):
$$\frac{1}{R_{eq}} = \frac{10}{150} + \frac{5}{150} + \frac{3}{150} = \frac{18}{150}$$

Now, take the reciprocal:
$$R_{eq} = \frac{150}{18}$$
**$R_{eq} \approx 8.33 \, \Omega$**

### Step 2: Calculate Total Current ($I$)
Using Ohm's Law:
$$I = \frac{12 \, \text{V}}{8.33 \, \Omega}$$
**$I \approx 1.44 \, \text{A}$**

---

## 5. Summary Table
| Connection Type | Total Resistance ($R_{eq}$) | Total Current ($I$) |
| :--- | :--- | :--- |
| **Series** | $95 \, \Omega$ | $0.126 \, \text{A}$ |
| **Parallel** | $8.33 \, \Omega$ | $1.44 \, \text{A}$ |

---

