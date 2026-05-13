# ⚡ Physics Basics: AC Voltage Equation Analysis

## 1. Problem Statement
Based on **image_1cab19.png**, the current in an AC circuit is given by the equation:
$$I(t) = 2 \sin(120\pi t)$$
The circuit consists of a single resistor with a resistance of **$50 \, \Omega$**. We need to determine the mathematical equation for the voltage $V(t)$ across this resistor.

---

## 2. Fundamental Physics Principles

### A. Ohm's Law in AC Circuits
For a purely resistive AC circuit, Ohm's Law applies to the instantaneous values of voltage and current just as it does in DC:
$$V(t) = I(t) \cdot R$$

### B. Phase Relationship
In a pure resistor, the voltage and current are **in phase**. This means they reach their maximum and minimum values at the same time. Consequently, the sine function for both will have the exact same angular frequency ($\omega$) and phase constant.



### C. Peak Voltage Relationship
The relationship between the peak (maximum) voltage ($V_{peak}$) and peak current ($I_{peak}$) is:
$$V_{peak} = I_{peak} \cdot R$$

---

## 3. Step-by-Step Calculation

### Step 1: Identify Parameters from the Current Equation
The given current equation is $I(t) = 2 \sin(120\pi t)$.
*   **Peak Current ($I_{peak}$):** $2 \, \text{A}$
*   **Angular Frequency ($\omega$):** $120\pi \, \text{rad/s}$

### Step 2: Calculate Peak Voltage ($V_{peak}$)
Using the peak current and the resistance value from the problem:
$$V_{peak} = I_{peak} \times R$$
$$V_{peak} = 2 \, \text{A} \times 50 \, \Omega$$
**$V_{peak} = 100 \, \text{V}$**

### Step 3: Construct the Final Voltage Equation
Since there is no phase shift in a purely resistive circuit, we keep the same sine argument $(120\pi t)$ and use our new peak voltage:
$$V(t) = V_{peak} \sin(\omega t)$$
**$V(t) = 100 \sin(120\pi t)$**

---

## 4. Final Result
The equation for the voltage across the resistor in is:
**$$V(t) = 100 \sin(120\pi t) \, \text{V}$$**

---