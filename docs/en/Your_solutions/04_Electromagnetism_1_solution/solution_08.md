# Physics Basics: Lorentz Force

## 1. Problem Description
A charged particle enters a uniform magnetic field. We need to calculate the magnitude of the **Lorentz force** acting on this particle given its charge, velocity, and the magnetic field strength, specifically when the motion is perpendicular to the field.

## 2. Given Data
* **Charge ($q$):** $2 \times 10^{-19} \text{ C}$
* **Mass ($m$):** $4 \times 10^{-27} \text{ kg}$
* **Magnetic Field ($B$):** $0.5 \text{ T}$
* **Velocity ($v$):** $10^6 \text{ m/s}$
* **Angle ($\theta$):** $90^\circ$ (Perpendicular to the field)

## 3. Physical Principles
The general **Lorentz Force** equation is given by $\mathbf{F} = q(\mathbf{E} + \mathbf{v} \times \mathbf{B})$. Since there is no mentioned electric field ($E = 0$), the force is entirely due to the magnetic field.

**Magnitude of Magnetic Force:**
$$F = q \cdot v \cdot B \cdot \sin(\theta)$$

Where:
* $F$ is the force in Newtons (N).
* $q$ is the electric charge in Coulombs (C).
* $v$ is the velocity in meters per second (m/s).
* $B$ is the magnetic field in Teslas (T).
* $\theta$ is the angle between the velocity and the magnetic field.

## 4. Step-by-Step Solution

### Step 1: Determining the Sine of the Angle
Because the particle is moving **perpendicularly** to the field:
$$\theta = 90^\circ$$
$$\sin(90^\circ) = 1$$
This means the force is at its maximum possible value for these parameters.

### Step 2: Substituting the Values
Plug the given numbers into the simplified formula $F = q v B$:
$$F = (2 \times 10^{-19} \text{ C}) \cdot (10^6 \text{ m/s}) \cdot (0.5 \text{ T})$$

### Step 3: Final Calculation
Group the coefficients and the powers of ten:
$$F = (2 \cdot 0.5) \times (10^{-19} \cdot 10^6)$$
$$F = 1.0 \times 10^{-13} \text{ N}$$

## 5. Conclusion
The magnitude of the Lorentz force acting on the particle is:
**$$F = 1.0 \times 10^{-13} \text{ N}$$**

> **Pro Tip:** In this specific question, the **mass** ($m$) is "extra information." It doesn't affect the force magnitude itself, but it would determine the particle's **acceleration** ($a = F/m$) or the **radius** of its circular path.