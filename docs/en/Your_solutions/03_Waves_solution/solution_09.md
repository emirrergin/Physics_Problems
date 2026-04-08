### Question 9: Damped Harmonic Oscillator (Ultra-Detailed Breakdown)

**1. General Theoretical Analysis**

The equation of motion for a damped harmonic oscillator is a second-order linear homogeneous differential equation:
$$m \frac{d^2x}{dt^2} + b \frac{dx}{dt} + kx = 0$$

To solve this, we divide by $m$ and define two key parameters:
* **Damping constant ($\gamma$):** $\gamma = \frac{b}{2m}$
* **Undamped natural frequency ($\omega_0$):** $\omega_0 = \sqrt{\frac{k}{m}}$

The equation becomes:
$$\ddot{x} + 2\gamma \dot{x} + \omega_0^2 x = 0$$

Substituting a trial solution $x(t) = e^{rt}$ leads to the characteristic equation:
$$r^2 + 2\gamma r + \omega_0^2 = 0$$
Using the quadratic formula, the roots are:
$$r_{1,2} = -\gamma \pm \sqrt{\gamma^2 - \omega_0^2}$$

---

**2. Classification of Damping Cases**

The behavior is determined by the term under the square root (the discriminant):

| Case | Condition | Physical Behavior | General Solution Form |
| :--- | :--- | :--- | :--- |
| **Underdamped** | $\gamma < \omega_0$ | System oscillates with decaying amplitude. | $x(t) = e^{-\gamma t}(A \cos(\omega_d t) + B \sin(\omega_d t))$ |
| **Critically Damped**| $\gamma = \omega_0$ | System returns to equilibrium as fast as possible without oscillating. | $x(t) = (A + Bt)e^{-\gamma t}$ |
| **Overdamped** | $\gamma > \omega_0$ | System returns to equilibrium slowly without oscillating. | $x(t) = Ae^{r_1 t} + Be^{r_2 t}$ |

*Note: $\omega_d = \sqrt{\omega_0^2 - \gamma^2}$ is the damped frequency.*


---

**3. Numerical Solution (RK4 Method Logic)**

To solve this numerically using the 4th Order Runge-Kutta (RK4) method, we reduce the 2nd order ODE into a system of two 1st order ODEs:
1. Let $v = \frac{dx}{dt}$
2. Then $\frac{dv}{dt} = -\frac{b}{m}v - \frac{k}{m}x$

For each time step $h$, we calculate four "slopes" ($k_1$ to $k_4$) for both $x$ and $v$ to predict the next value with high precision.

---

**4. Interactive HTML Simulation Code**

The following code uses HTML5 Canvas and JavaScript to implement the RK4 solver. It includes a slider for $b$ and real-time generation of the $x(t)$ graph and Phase Portrait ($v$ vs $x$).