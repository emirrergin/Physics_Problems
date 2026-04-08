### Question 11: Two-Slit Interference (Ultra-Detailed Breakdown)

**1. Theoretical Framework: Young's Double Slit Experiment**
In this simulation, we treat the two slits as coherent point sources located at $\vec{r}_1$ and $\vec{r}_2$. Coherence implies that the sources have a constant phase relationship and the same frequency.

The resulting displacement $u(\vec{r}, t)$ at any observation point $\vec{r}$ is calculated by:
$$u(\vec{r}, t) = \frac{A}{d_1} \sin(k d_1 - \omega t) + \frac{A}{d_2} \sin(k d_2 - \omega t)$$

Where:
* $d_1 = |\vec{r} - \vec{r}_1|$ and $d_2 = |\vec{r} - \vec{r}_2|$ are the distances from the point $\vec{r}$ to source 1 and source 2 respectively.
* **Constructive Interference:** Occurs when the path difference $\Delta d = |d_1 - d_2|$ is an integer multiple of the wavelength ($n\lambda$).
* **Destructive Interference:** Occurs when the path difference is a half-integer multiple of the wavelength ($(n + 1/2)\lambda$).

**2. Key Parameters to Manipulate:**
* **Slit Distance ($d$):** Changing this alters the angular separation of the interference fringes.
* **Wavelength ($\lambda$):** Since $k = 2\pi/\lambda$, changing $\lambda$ changes the "density" of the wave crests.

---

**3. Interactive HTML/JavaScript Implementation**

This code calculates the wave interference on every pixel in real-time. It includes sliders for the distance between the slits and the wavelength.