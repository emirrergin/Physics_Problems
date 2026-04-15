# Physics Basics: Coulomb's Law (Square Configuration)

## 1. Problem Description
Four point charges of $+1.0 \text{ C}$ each are placed at the corners of a square with sides of $1.0 \text{ m}$. Calculate the magnitude and direction of the net electric force acting on a charge of $-2.0 \text{ C}$ placed at the center of the square.

## 2. Given Data
* **Corner Charges ($q_1, q_2, q_3, q_4$):** $+1.0 \text{ C}$ each.
* **Center Charge ($q_0$):** $-2.0 \text{ C}$.
* **Side Length ($a$):** $1.0 \text{ m}$.
* **Coulomb's Constant ($k$):** $\approx 8.99 \times 10^9 \text{ N}\cdot\text{m}^2/\text{C}^2$.

## 3. Physical Principles
1. **Coulomb's Law:** The magnitude of the force between two point charges is given by:
   $$F = k \frac{|q_1 q_2|}{r^2}$$
2. **Superposition Principle:** The net force on a charge is the vector sum of all individual forces acting on it:
   $$\vec{F}_{net} = \sum \vec{F}_i$$
3. **Symmetry:** In a highly symmetric arrangement (like a square with identical corner charges), opposing force vectors may cancel each other out.

## 4. Step-by-Step Solution

### Step 1: Geometry Analysis
To calculate the force, we first need the distance ($r$) from any corner to the center of the square.
* The diagonal ($d$) of a square with side $a$ is: $d = a\sqrt{2}$.
* Since the center is at the midpoint of the diagonal:
  $$r = \frac{a\sqrt{2}}{2} = \frac{1.0 \cdot \sqrt{2}}{2} \approx 0.707 \text{ m}$$
* The square of the distance is:
  $$r^2 = \left(\frac{\sqrt{2}}{2}\right)^2 = \frac{2}{4} = 0.5 \text{ m}^2$$

### Step 2: Individual Force Magnitudes
Because all corner charges are identical and the distances are the same, the magnitude of the force from each corner charge on the center charge is equal:
$$F = k \frac{|(1.0 \text{ C})(-2.0 \text{ C})|}{0.5 \text{ m}^2}$$
$$F = (8.99 \times 10^9) \cdot \frac{2}{0.5}$$
$$F = 35.96 \times 10^9 \text{ N}$$

### Step 3: Vector Addition and Symmetry
Let's name the corners $A, B, C,$ and $D$ in clockwise order.
* The center charge is **negative**, and the corner charges are **positive**. Therefore, the forces are **attractive**.
* **Force from Corner A ($\vec{F}_A$):** Points from the center toward corner A.
* **Force from Corner C ($\vec{F}_C$):** (Opposite to A) Points from the center toward corner C.

Since $|\vec{F}_A| = |\vec{F}_C|$ and they point in exactly opposite directions along the same diagonal:
$$\vec{F}_A + \vec{F}_C = 0$$

Similarly, for the other diagonal:
* **Force from Corner B ($\vec{F}_B$):** Points toward corner B.
* **Force from Corner D ($\vec{F}_D$):** Points toward corner D.
$$\vec{F}_B + \vec{F}_D = 0$$

### Step 4: Net Force Calculation
$$\vec{F}_{net} = \vec{F}_A + \vec{F}_B + \vec{F}_C + \vec{F}_D$$
$$\vec{F}_{net} = (\vec{F}_A + \vec{F}_C) + (\vec{F}_B + \vec{F}_D)$$
$$\vec{F}_{net} = 0 + 0 = 0$$

## 5. Conclusion
* **Magnitude:** The magnitude of the net electric force is **$0 \text{ N}$**.
* **Direction:** Since the magnitude is zero, there is **no direction**.

> **Conceptual Note:** This result holds true for any value of the center charge $q_0$, as long as the four corner charges are identical and placed at equal distances. The symmetry of the system ensures that every "pull" is countered by an equal and opposite "pull" from the opposite corner.