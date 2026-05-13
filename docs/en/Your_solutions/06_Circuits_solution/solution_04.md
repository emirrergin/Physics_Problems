# 🧩 Physics Basics: Mixed Circuit Analysis - Problem 4

## 1. Problem Statement
we need to calculate the total equivalent resistance ($R_{eq}$) for the given mixed circuit.

**Given:**
* All resistors in the circuit have a resistance of **$10 \, \Omega$**.
* There are **6 resistors** arranged in a combination of series and parallel branches.

---

## 2. Step-by-Step Circuit Reduction

To find the equivalent resistance, we simplify the circuit from the most internal sections outward.

### Step 1: Simplify the Upper Branch ($R_{top}$)
The top branch of the parallel section consists of two resistors connected in series.
$$R_{top} = 10 \, \Omega + 10 \, \Omega = 20 \, \Omega$$

### Step 2: Simplify the Parallel Pair in the Lower Branch ($R_{p1}$)
Within the lower branch, there is a small section where two resistors are in parallel.
$$\frac{1}{R_{p1}} = \frac{1}{10} + \frac{1}{10} = \frac{2}{10} \implies R_{p1} = 5 \, \Omega$$

### Step 3: Simplify the Total Lower Branch ($R_{bot}$)
The $5 \, \Omega$ equivalent resistance we just calculated is in series with the resistor to its left in that same branch.
$$R_{bot} = 10 \, \Omega + 5 \, \Omega = 15 \, \Omega$$

### Step 4: Combine the Main Parallel Branches ($R_{parallel}$)
Now, we combine the simplified top branch ($20 \, \Omega$) and bottom branch ($15 \, \Omega$) which are in parallel with each other.
$$R_{parallel} = \frac{R_{top} \times R_{bot}}{R_{top} + R_{bot}} = \frac{20 \times 15}{20 + 15} = \frac{300}{35} = \frac{60}{7} \approx 8.57 \, \Omega$$

### Step 5: Final Total Equivalent Resistance ($R_{eq}$)
The entire parallel block we just analyzed is in series with the last resistor on the far right.
$$R_{eq} = R_{parallel} + 10 \, \Omega$$
$$R_{eq} = 8.57 \, \Omega + 10 \, \Omega = 18.57 \, \Omega$$

---

## 3. Final Result
The total equivalent resistance of the circuit shown in **image_1cba58.png** is **$18.57 \, \Omega$**.

---

