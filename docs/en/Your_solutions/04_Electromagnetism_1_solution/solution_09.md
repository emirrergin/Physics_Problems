# Physics Basics: Vector Lorentz Force

## 1. Problem Description
A proton moves with a velocity vector $\vec{v} = (2\hat{i} - 4\hat{j} + \hat{k}) \text{ m/s}$ in a region with a magnetic field $\vec{B} = (\hat{i} + 2\hat{j} - \hat{k}) \text{ T}$. Calculate the magnitude of the magnetic force ($F_m$) experienced by the proton.

## 2. Given Data
* **Velocity ($\vec{v}$):** $(2, -4, 1) \text{ m/s}$
* **Magnetic Field ($\vec{B}$):** $(1, 2, -1) \text{ T}$
* **Charge of a proton ($q$):** $\approx 1.6 \times 10^{-19} \text{ C}$
* **Goal:** Find the magnitude of the force vector $|\vec{F}_m|$.

## 3. Physical Principles
The magnetic force on a moving charge is given by the vector Lorentz force equation (excluding the electric field component):
$$\vec{F}_m = q (\vec{v} \times \vec{B})$$

The magnitude of this force is:
$$F_m = |q| \cdot |\vec{v} \times \vec{B}|$$

## 4. Step-by-Step Solution

### Step 1: Calculate the Cross Product $(\vec{v} \times \vec{B})$
We use the determinant method for the cross product:
$$\vec{v} \times \vec{B} = \begin{vmatrix} \hat{i} & \hat{j} & \hat{k} \\ 2 & -4 & 1 \\ 1 & 2 & -1 \end{vmatrix}$$

Expanding the determinant:
* **$\hat{i}$ component:** $(-4)(-1) - (1)(2) = 4 - 2 = 2$
* **$\hat{j}$ component:** $-[(2)(-1) - (1)(1)] = -[-2 - 1] = 3$
* **$\hat{k}$ component:** $(2)(2) - (-4)(1) = 4 + 4 = 8$

So, the cross product vector is:
$$\vec{v} \times \vec{B} = (2\hat{i} + 3\hat{j} + 8\hat{k})$$

### Step 2: Calculate the Magnitude of the Cross Product
$$|\vec{v} \times \vec{B}| = \sqrt{(2)^2 + (3)^2 + (8)^2}$$
$$|\vec{v} \times \vec{B}| = \sqrt{4 + 9 + 64}$$
$$|\vec{v} \times \vec{B}| = \sqrt{77} \approx 8.775 \text{ T}\cdot\text{m/s}$$

### Step 3: Calculate the Final Force Magnitude
Now, multiply the result by the charge of the proton ($q$):
$$F_m = (1.6 \times 10^{-19} \text{ C}) \cdot \sqrt{77}$$
$$F_m \approx (1.6 \times 10^{-19}) \cdot (8.775)$$
$$F_m \approx 1.404 \times 10^{-18} \text{ N}$$

## 5. Conclusion
The magnitude of the magnetic force experienced by the proton is approximately:
**$$F_m \approx 1.40 \times 10^{-18} \text{ N}$$**

> **Note:** The direction of this force is defined by the vector $(2\hat{i} + 3\hat{j} + 8\hat{k})$. Since the charge is positive, the force points exactly in the direction of the cross product result.