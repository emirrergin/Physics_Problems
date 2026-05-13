# 📉 Physics Basics: RLC Circuits & Mechanical Analogies

## 1. Problem Statement
we need to:
1. Write the **differential equation** for a series RLC circuit.
2. Compare it to the **damped harmonic oscillator** equation.
3. Identify the **analogies** between the terms of these two physical systems.

---

## 2. The Series RLC Differential Equation
In a series RLC circuit, according to **Kirchhoff's Voltage Law (KVL)**, the sum of voltage drops across the inductor ($L$), resistor ($R$), and capacitor ($C$) must equal the applied voltage ($V$).



### Derivation Steps:
1. **Kirchhoff's Equation:**
   $$V_L(t) + V_R(t) + V_C(t) = V(t)$$
2. **Substitute Component Definitions:**
   $$L \frac{dI(t)}{dt} + R I(t) + V_C(t) = V(t)$$
3. **Relation between Current ($I$) and Capacitor Voltage ($V_C$):**
   Since $I(t) = C \frac{dV_C(t)}{dt}$, then $\frac{dI(t)}{dt} = C \frac{d^2V_C(t)}{dt^2}$.
4. **Final Second-Order Differential Equation:**
   $$LC \frac{d^2V_C(t)}{dt^2} + RC \frac{dV_C(t)}{dt} + V_C(t) = V(t)$$

---

## 3. The Damped Harmonic Oscillator Equation
For a mechanical mass-spring-damper system, Newton’s Second Law gives us the following differential equation for displacement ($x$):



$$m \frac{d^2x(t)}{dt^2} + b \frac{dx(t)}{dt} + k x(t) = F(t)$$

Where:
*   **$m$**: Mass (Inertia)
*   **$b$**: Damping constant (Friction)
*   **$k$**: Spring constant (Stiffness)
*   **$F(t)$**: External driving force

---

## 4. Physical Analogies (The Comparison)
By comparing the two equations, we can see that electrical components play the same mathematical roles as mechanical components.

| Mechanical Term | Symbol | Electrical Analogue (Charge $q$ basis) | Symbol |
| :--- | :---: | :--- | :---: |
| **Displacement** | $x$ | **Electric Charge** ($q = C V_C$) | $q$ |
| **Velocity** | $v = \dot{x}$ | **Electric Current** | $I$ |
| **Mass** | $m$ | **Inductance** | $L$ |
| **Damping** | $b$ | **Resistance** | $R$ |
| **Spring Constant** | $k$ | **Reciprocal of Capacitance** | $1/C$ |
| **Driving Force** | $F$ | **Applied Voltage** | $V$ |

---

## 5. Final Comparison Result
The RLC circuit is essentially an **electronic oscillator**. The inductor stores energy in a magnetic field (like kinetic energy in a mass), the capacitor stores energy in an electric field (like potential energy in a spring), and the resistor dissipates energy (like friction/damping).

---