# 🧲 Physics Basics: Ampere's Law & Magnetic Fields

## 1. Problem Statement
Two long, parallel wires are **$10 \, \text{cm}$** apart and carry currents of **$5 \, \text{A}$** in **opposite directions**. Calculate the magnitude and direction of the magnetic field at a point **midway** between the wires.

---

## 2. Fundamental Physics Principles

### A. Magnetic Field of a Long Straight Wire
According to Ampere's Law, the magnetic field ($B$) produced by a long straight wire carrying a current ($I$) at a distance ($r$) is given by:
$$B = \frac{\mu_0 I}{2 \pi r}$$

Where:
* **$\mu_0$**: Permeability of free space ($4\pi \times 10^{-7} \, \text{T}\cdot\text{m/A}$)
* **$I$**: Current in Amperes
* **$r$**: Distance from the wire in meters

### B. The Right-Hand Rule (RHR)
To find the **direction** of the magnetic field, we use the Right-Hand Rule:
1. Point your thumb in the direction of the current ($I$).
2. Your fingers will curl in the direction of the magnetic field lines ($B$).

### C. Principle of Superposition
The total magnetic field at any point is the vector sum of the individual fields produced by each wire:
$$\vec{B}_{total} = \vec{B}_1 + \vec{B}_2$$

---

## 3. Given Information
* **Current ($I_1$ and $I_2$):** $5 \, \text{A}$ (Opposite directions)
* **Total Distance ($d$):** $10 \, \text{cm} = 0.1 \, \text{m}$
* **Distance to Midway Point ($r$):** $0.1 / 2 = 0.05 \, \text{m}$

---

## 4. Step-by-Step Solution

### Step 1: Determine the Direction (The Logic)
Let's assume **Wire 1** is on the left with current going **UP**, and **Wire 2** is on the right with current going **DOWN**.

1. **Wire 1 (Up):** Using RHR, at the midpoint (to its right), the field points **INTO** the page.
2. **Wire 2 (Down):** Using RHR, at the midpoint (to its left), the field also points **INTO** the page.

**Conclusion:** Since both fields point in the same direction at the midpoint, we **ADD** their magnitudes.


### Step 2: Calculate Magnitude of One Wire
$$B_1 = \frac{(4\pi \times 10^{-7}) \times 5}{2 \pi \times 0.05}$$

Simplify by canceling $2\pi$:
$$B_1 = \frac{2 \times 10^{-7} \times 5}{0.05}$$
$$B_1 = \frac{10 \times 10^{-7}}{0.05} = 200 \times 10^{-7}$$
$$B_1 = 2.0 \times 10^{-5} \, \text{T}$$

### Step 3: Calculate Total Magnitude
Since $I_1 = I_2$ and both wires are at the same distance ($r = 0.05 \, \text{m}$):
$$B_{total} = B_1 + B_2$$
$$B_{total} = 2.0 \times 10^{-5} + 2.0 \times 10^{-5}$$
$$B_{total} = 4.0 \times 10^{-5} \, \text{T}$$

---

## 5. Final Result
* **Magnitude:** $4.0 \times 10^{-5} \, \text{T}$ (or $40 \, \mu\text{T}$)
* **Direction:** The field points in the same direction from both wires (e.g., "into the page" if Wire 1 is up and Wire 2 is down).

---

