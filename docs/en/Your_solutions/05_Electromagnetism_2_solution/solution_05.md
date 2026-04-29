# 🔋 Physics Basics: Parallel-Plate Capacitor Analysis

## 1. Problem Statement
We have a parallel-plate capacitor with the following parameters:
* **Surface Area ($S$):** $0.02 \, \text{m}^2$
* **Distance between plates ($d$):** $5 \, \text{mm} = 0.005 \, \text{m}$
* **Voltage ($V$ or $U_{voltage}$):** $500 \, \text{V}$

We need to calculate the capacitance ($C$), stored energy ($U_{energy}$), electric field intensity ($E$), and the force of attraction ($F$) between the plates.

---

## 2. Fundamental Physics Constants & Formulas
To solve this, we use the following constants and relationships:
* **Permittivity of free space ($\varepsilon_0$):** $\approx 8.854 \times 10^{-12} \, \text{F/m}$
* **Capacitance:** $C = \varepsilon_0 \frac{S}{d}$
* **Stored Energy:** $W = \frac{1}{2} C V^2$
* **Electric Field:** $E = \frac{V}{d}$
* **Force of Attraction:** $F = \frac{1}{2} \varepsilon_0 S E^2$ (or $F = \frac{1}{2} Q E$)


---

## 3. Step-by-Step Calculations

### Step 1: Calculate Capacitance ($C$)
Using the geometric formula for a parallel-plate capacitor:
$$C = \varepsilon_0 \frac{S}{d}$$
$$C = (8.854 \times 10^{-12}) \cdot \frac{0.02}{0.005}$$
$$C = (8.854 \times 10^{-12}) \cdot 4$$
**$C \approx 3.54 \times 10^{-11} \, \text{F}$** (or $35.4 \, \text{pF}$)

---

### Step 2: Calculate Stored Energy ($U_{energy}$)
The energy stored in the electric field is:
$$W = \frac{1}{2} C V^2$$
$$W = 0.5 \cdot (3.54 \times 10^{-11}) \cdot (500)^2$$
$$W = 0.5 \cdot (3.54 \times 10^{-11}) \cdot 250,000$$
**$W \approx 4.43 \times 10^{-6} \, \text{J}$** (or $4.43 \, \mu\text{J}$)

---

### Step 3: Calculate Electric Field Intensity ($E$)
The electric field between the plates is uniform and calculated as:
$$E = \frac{V}{d}$$
$$E = \frac{500}{0.005}$$
**$E = 100,000 \, \text{V/m}$** (or $10^5 \, \text{V/m}$)


---

### Step 4: Calculate Force of Attraction ($F$)
The plates have opposite charges and attract each other. The force is:
$$F = \frac{1}{2} \varepsilon_0 S E^2$$
$$F = 0.5 \cdot (8.854 \times 10^{-12}) \cdot 0.02 \cdot (100,000)^2$$
$$F = (8.854 \times 10^{-14}) \cdot 10^{10}$$
**$F \approx 8.85 \times 10^{-4} \, \text{N}$**

---

## 4. Final Results Summary
| Parameter | Symbol | Value | Unit |
| :--- | :---: | :--- | :--- |
| **Capacitance** | $C$ | $3.54 \times 10^{-11}$ | $\text{F}$ |
| **Stored Energy** | $U$ | $4.43 \times 10^{-6}$ | $\text{J}$ |
| **Electric Field** | $E$ | $100,000$ | $\text{V/m}$ |
| **Attraction Force** | $F$ | $8.85 \times 10^{-4}$ | $\text{N}$ |

---

