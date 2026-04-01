## Simple Pendulum Formula (Reminder)

The period of a simple pendulum (the time it takes to complete one full swing) is calculated using the following formula:

$$T = 2\pi\sqrt{\frac{L}{g}}$$

Where:
* $T$: Period (in seconds)
* $L$: Length of the string (in meters)
* $g$: Gravitational acceleration at the location (in m/s²)

---

### Question 1: Calculating the Period on the Moon

**Question:** A simple pendulum has a period of 4 seconds on Earth. What would its period be on the Moon, where the gravitational acceleration is about 1/6th of Earth's?

**Solution:**
If we let $g$ be the gravitational acceleration on Earth, the gravitational acceleration on the Moon is $\frac{g}{6}$. 

1. Let's write the formula for the situation on Earth:
$$T_{Earth} = 2\pi\sqrt{\frac{L}{g}} = 4 \text{ seconds}$$

2. Let's write the formula for the situation on the Moon:
$$T_{Moon} = 2\pi\sqrt{\frac{L}{\frac{g}{6}}}$$

3. Let's invert the $\frac{1}{6}$ in the Moon's formula and bring it up as a multiplier:
$$T_{Moon} = 2\pi\sqrt{6 \cdot \frac{L}{g}}$$

4. Let's take the factor of 6 out of the square root as a separate root:
$$T_{Moon} = \sqrt{6} \cdot \left(2\pi\sqrt{\frac{L}{g}}\right)$$

5. We know the expression in the parentheses is equal to the period on Earth ($T_{Earth}$). Let's substitute it:
$$T_{Moon} = \sqrt{6} \cdot 4$$

**Result:**
The period on the Moon will be exactly **$4\sqrt{6}$ seconds** (If we take $\sqrt{6} \approx 2.45$, it is approximately $4 \cdot 2.45 = 9.8$ seconds).

---

### Question 2: Calculating the String Length for a 1-Second Period

**Question:** What is the required length of a simple pendulum to have a period of exactly 1 second on Earth?

**Solution:**
In this question, we need to take the period ($T$) as 1 second and find the length ($L$). We will use the standard gravitational acceleration on Earth as $g = 9.8 \text{ m/s}^2$.

1. Let's write the formula and plug in the knowns:
$$1 = 2\pi\sqrt{\frac{L}{g}}$$

2. Square both sides of the equation to eliminate the square root:
$$1^2 = (2\pi)^2 \cdot \left(\sqrt{\frac{L}{g}}\right)^2$$
$$1 = 4\pi^2 \cdot \frac{L}{g}$$

3. Isolate the length ($L$). First, multiply both sides by $g$, then divide by $4\pi^2$:
$$g = 4\pi^2 \cdot L$$
$$L = \frac{g}{4\pi^2}$$

4. Substitute the values ($g \approx 9.8$ and $\pi \approx 3.14$):
$$L = \frac{9.8}{4 \cdot (3.14)^2}$$
$$L \approx \frac{9.8}{4 \cdot 9.8596}$$
$$L \approx \frac{9.8}{39.4384}$$
$$L \approx 0.248 \text{ meters}$$

**Result:**
The length of the pendulum should be approximately **0.248 meters** (or **24.8 cm**). 

*(Note: In basic physics, for ease of calculation, $g \approx \pi^2$ is sometimes assumed. If you use this approximation, the formula becomes $L = \frac{\pi^2}{4\pi^2}$ and the exact result is $\frac{1}{4}$ meter, which is exactly **25 cm**.)*