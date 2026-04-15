# Physics Basics: Lorentz Force acting on a Wire

## 1. Problem Description
Calculate the magnetic force ($F$) acting on a straight wire that is $2.0 \text{ m}$ long, carries a current of $10 \text{ A}$, and is placed in a uniform magnetic field of $B = 0.5 \text{ T}$. We need to find the force for three different angles ($\theta$) between the wire and the field:
* **a)** $90^\circ$
* **b)** $45^\circ$
* **c)** $0^\circ$

## 2. Given Data
* **Length of wire ($L$):** $2.0 \text{ m}$
* **Current ($I$):** $10 \text{ A}$
* **Magnetic Field ($B$):** $0.5 \text{ T}$
* **Goal:** Calculate $F$ for $\theta = 90^\circ, 45^\circ, 0^\circ$

## 3. Physical Principles
The magnetic force exerted on a current-carrying wire in a uniform magnetic field is given by the formula:
**$$F = I \cdot L \cdot B \cdot \sin(\theta)$$**

Where:
* $F$ is the force (Newtons)
* $I$ is the current (Amperes)
* $L$ is the length (Meters)
* $B$ is the magnetic field (Teslas)
* $\theta$ is the angle between the direction of the current and the magnetic field.

## 4. Step-by-Step Solution

### Common Product ($I \cdot L \cdot B$)
First, let's calculate the constant part of the equation:
$$I \cdot L \cdot B = 10 \text{ A} \cdot 2.0 \text{ m} \cdot 0.5 \text{ T} = 10 \text{ N}$$

---

### Case a) $\theta = 90^\circ$ (Perpendicular)
When the wire is perpendicular to the field, the force is at its maximum.
* $\sin(90^\circ) = 1$
$$F_a = 10 \cdot 1 = 10 \text{ N}$$

### Case b) $\theta = 45^\circ$
When the wire is at a diagonal:
* $\sin(45^\circ) = \frac{\sqrt{2}}{2} \approx 0.707$
$$F_b = 10 \cdot 0.707$$
**$$F_b \approx 7.07 \text{ N}$$**

### Case c) $\theta = 0^\circ$ (Parallel)
When the wire is parallel to the magnetic field, no magnetic force is exerted.
* $\sin(0^\circ) = 0$
$$F_c = 10 \cdot 0 = 0 \text{ N}$$

## 5. Summary Table

| Angle ($\theta$) | $\sin(\theta)$ | Force ($F$) |
| :--- | :--- | :--- |
| $90^\circ$ (Perpendicular) | $1.0$ | **$10.0 \text{ N}$** |
| $45^\circ$ | $0.707$ | **$7.07 \text{ N}$** |
| $0^\circ$ (Parallel) | $0.0$ | **$0.0 \text{ N}$** |

## 6. Conclusion
The magnetic force is highly dependent on the orientation of the wire. It reaches its **maximum** value when the wire is perpendicular to the field and drops to **zero** when the wire is aligned parallel to the field lines.