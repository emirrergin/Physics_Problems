## Vertical Throw with Drag Analysis

**Given Equation of Motion:**
$$m\frac{dv}{dt} = -mg - kv$$
With initial conditions: $v(0) = v_0$ and $x(0) = 10$.

---

### 1. Analytical Solution

**Solving for Velocity $v(t)$:**
First, we separate the variables to solve the first-order differential equation. Let's define the terminal velocity as $v_T = \frac{mg}{k}$ to simplify the notation.
$$m\frac{dv}{dt} = -k\left(\frac{mg}{k} + v\right) = -k(v_T + v)$$
$$\frac{dv}{v_T + v} = -\frac{k}{m}dt$$

Integrate both sides:
$$\int \frac{1}{v_T + v} dv = \int -\frac{k}{m} dt$$
$$\ln|v_T + v| = -\frac{k}{m}t + C_1$$

Apply the initial condition $v(0) = v_0$ to find $C_1$:
$$C_1 = \ln|v_T + v_0|$$

Substitute $C_1$ back and solve for $v(t)$:
$$\ln\left(\frac{v_T + v}{v_T + v_0}\right) = -\frac{k}{m}t$$
$$v(t) = (v_0 + v_T)e^{-\frac{k}{m}t} - v_T$$
*(Substituting back $v_T$, we get $v(t) = (v_0 + \frac{mg}{k})e^{-\frac{k}{m}t} - \frac{mg}{k}$)*

**Solving for Position $x(t)$:**
Since $v(t) = \frac{dx}{dt}$, we integrate $v(t)$ to find the position:
$$x(t) = \int \left[ (v_0 + v_T)e^{-\frac{k}{m}t} - v_T \right] dt$$
$$x(t) = -\frac{m}{k}(v_0 + v_T)e^{-\frac{k}{m}t} - v_Tt + C_2$$

Apply the initial condition $x(0) = 10$:
$$10 = -\frac{m}{k}(v_0 + v_T)(1) - 0 + C_2$$
$$C_2 = 10 + \frac{m}{k}(v_0 + v_T)$$

Substitute $C_2$ back to get the final equation for position:
$$x(t) = 10 + \frac{m}{k}(v_0 + v_T)\left(1 - e^{-\frac{k}{m}t}\right) - v_Tt$$

---

### 2. Determine the Maximum Height

The maximum height occurs when the velocity reaches zero ($v(t_{max}) = 0$).
$$0 = (v_0 + v_T)e^{-\frac{k}{m}t_{max}} - v_T$$
$$e^{-\frac{k}{m}t_{max}} = \frac{v_T}{v_0 + v_T}$$

Take the natural logarithm of both sides to find the time to maximum height ($t_{max}$):
$$t_{max} = \frac{m}{k} \ln\left(\frac{v_0 + v_T}{v_T}\right) = \frac{m}{k} \ln\left(1 + \frac{kv_0}{mg}\right)$$

Now, substitute $t_{max}$ and $e^{-\frac{k}{m}t_{max}}$ into the $x(t)$ equation:
$$x_{max} = 10 + \frac{m}{k}(v_0 + v_T)\left(1 - \frac{v_T}{v_0 + v_T}\right) - v_T \left[ \frac{m}{k} \ln\left(1 + \frac{v_0}{v_T}\right) \right]$$
$$x_{max} = 10 + \frac{m}{k}v_0 - \frac{m^2g}{k^2}\ln\left(1 + \frac{kv_0}{mg}\right)$$

---

### 3. Comparison with the Case Without Drag

**Without Drag ($k \to 0$):**
* **Equation of motion:** $m\frac{dv}{dt} = -mg \implies a = -g$
* **Velocity:** $v(t) = v_0 - gt$ (Decreases linearly)
* **Position:** $x(t) = 10 + v_0t - \frac{1}{2}gt^2$ (Parabolic trajectory)
* **Max Height Time:** $t_{max} = \frac{v_0}{g}$
* **Max Height:** $x_{max} = 10 + \frac{v_0^2}{2g}$

**Comparison:**
1.  **Maximum Height:** The drag force consistently opposes the upward motion, removing mechanical energy from the system. Therefore, the maximum height with drag is **lower** than the case without drag.
2.  **Time to Ascend:** The downward acceleration is greater with drag ($g + \frac{k}{m}v$) than without it (just $g$). Consequently, the object reaches its maximum height **faster** when air resistance is present.
3.  **Velocity Profile:** Without drag, velocity changes linearly. With drag, velocity decays exponentially towards a terminal velocity.

---

### 4. Numerical Simulation using HTML

Here is the graphic : 
