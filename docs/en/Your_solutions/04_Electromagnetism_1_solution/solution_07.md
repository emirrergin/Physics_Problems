# Physics Basics: Cyclotron Motion

## 1. Problem Description
An electron is accelerated from rest through a potential difference of $5000\text{ V}$. It then enters a region of uniform magnetic field $B = 0.1\text{ T}$, perpendicular to its velocity. What is the radius ($r$) of the circular path it will follow?

## 2. Constants & Given Data
* **Potential Difference ($V$):** $5000\text{ V}$
* **Magnetic Field ($B$):** $0.1\text{ T}$
* **Mass of electron ($m_e$):** $9.11 \times 10^{-31}\text{ kg}$
* **Charge of electron ($e$):** $1.6 \times 10^{-19}\text{ C}$
* **Initial Velocity ($v_0$):** $0\text{ m/s}$ (starts from rest)

## 3. Physical Principles
This problem is solved in two distinct phases:

### Phase 1: Acceleration (Conservation of Energy)
The work done by the electric field ($e \cdot V$) is converted entirely into the kinetic energy of the electron.
$$e \cdot V = \frac{1}{2} m v^2$$

### Phase 2: Circular Motion (Magnetic Force)
When a charged particle enters a magnetic field perpendicularly, the magnetic force acts as a centripetal force, causing the particle to move in a circle.
$$F_B = F_c \implies e v B = \frac{m v^2}{r}$$

## 4. Step-by-Step Solution

### Step 1: Calculate the Velocity ($v$)
Using the energy equation:
$$v = \sqrt{\frac{2eV}{m}}$$
$$v = \sqrt{\frac{2 \cdot (1.6 \times 10^{-19}\text{ C}) \cdot 5000\text{ V}}{9.11 \times 10^{-31}\text{ kg}}}$$
$$v = \sqrt{\frac{1.6 \times 10^{-15}}{9.11 \times 10^{-31}}}$$
$$v \approx 4.19 \times 10^7\text{ m/s}$$

### Step 2: Derive the Formula for Radius ($r$)
From the force balance equation ($evB = \frac{mv^2}{r}$), we solve for $r$:
$$r = \frac{m v}{e B}$$

### Step 3: Calculate the Final Radius
Substitute the velocity found in Step 1 into the radius formula:
$$r = \frac{(9.11 \times 10^{-31}\text{ kg}) \cdot (4.19 \times 10^7\text{ m/s})}{(1.6 \times 10^{-19}\text{ C}) \cdot 0.1\text{ T}}$$
$$r = \frac{3.817 \times 10^{-23}}{1.6 \times 10^{-20}}$$
**$$r \approx 2.39 \times 10^{-3}\text{ m}$$**

## 5. Conclusion
The radius of the circular path followed by the electron is approximately:
**$$r \approx 2.39\text{ mm}$$**

> **Technical Insight:** The radius of motion (often called the Larmor radius or gyroradius) is directly proportional to the particle's momentum and inversely proportional to the magnetic field strength. Because electrons are very light, they curve significantly even in relatively weak magnetic fields.