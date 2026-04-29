
## 1. Problem Statement
An electromagnetic wave's electric field is described by:
$$E_y(x, t) = 100 \sin(10^7 x - \omega t) \, \text{V/m}$$

**Goals:**
1. Determine the **direction of propagation**.
2. Calculate the **wavelength** ($\lambda$).
3. Calculate the **angular frequency** ($\omega$).
4. Write the **equation for the magnetic field component**.

---

## 2. Fundamental Physics Principles
The standard form for a traveling wave is:
$$E(x, t) = E_0 \sin(kx - \omega t)$$

Where:
* **$E_0$**: Amplitude ($100 \, \text{V/m}$)
* **$k$**: Wave number ($k = 2\pi / \lambda$)
* **$\omega$**: Angular frequency ($\omega = 2\pi f$)
* **Speed of Light ($c$):** In vacuum, $c = \omega / k \approx 3 \times 10^8 \, \text{m/s}$

---

## 3. Step-by-Step Solution

### Step 1: Direction of Propagation
Inside the sine function $(10^7 x - \omega t)$:
* The variable **$x$** means the wave moves along the x-axis.
* The **minus sign ($-$)** between $kx$ and $\omega t$ indicates the wave is moving in the **positive x-direction** ($+x$).

### Step 2: Calculate Wavelength ($\lambda$)
From the equation, the wave number $k$ is $10^7 \, \text{rad/m}$.
Using the formula $\lambda = 2\pi / k$:
$$\lambda = \frac{2\pi}{10^7}$$
$$\lambda \approx 6.28 \times 10^{-7} \, \text{m}$$

### Step 3: Calculate Angular Frequency ($\omega$)
For EM waves in vacuum/air: $\omega = c \cdot k$.
$$\omega = (3 \times 10^8) \cdot (10^7)$$
$$\omega = 3 \times 10^{15} \, \text{rad/s}$$

### Step 4: Magnetic Field Equation ($B$)
1. **Amplitude ($B_0$):** $B_0 = E_0 / c = 100 / (3 \times 10^8) \approx 3.33 \times 10^{-7} \, \text{T}$
2. **Phase:** Stays the same as the $E$ field.
3. **Direction:** Must be perpendicular to propagation ($+x$) and $E$ field ($y$). Therefore, it is in the **z-direction**.

**Final Equation:**
$$B_z(x, t) = (3.33 \times 10^{-7}) \sin(10^7 x - 3 \times 10^{15} t) \, \text{T}$$

---

## 4. Final Results Summary
| Property | Value |
| :--- | :--- |
| **Propagation Direction** | Positive x-axis ($+x$) |
| **Wavelength ($\lambda$)** | $6.28 \times 10^{-7} \, \text{m}$ |
| **Angular Frequency ($\omega$)** | $3 \times 10^{15} \, \text{rad/s}$ |
| **Magnetic Field Amplitude** | $3.33 \times 10^{-7} \, \text{T}$ |