# 🧩 Physics Basics: Combinations of Three Resistors

## 1. Problem Statement
we have a supply of exactly **three 1 $\Omega$ resistors**. The task is to identify and list all unique equivalent resistance ($R_{eq}$) values possible by combining all three of them.

---

## 2. Fundamental Physics Principles

### A. Resistors in Series
In a series connection, the total resistance is simply the sum of the individual components:
$$R_{series} = R_1 + R_2 + R_3$$

### B. Resistors in Parallel
In a parallel connection, the equivalent resistance is found using the sum of the reciprocals:
$$\frac{1}{R_{parallel}} = \frac{1}{R_1} + \frac{1}{R_2} + \frac{1}{R_3}$$

---

## 3. Step-by-Step Analysis of Combinations

There are **four unique ways** to arrange exactly three identical resistors:

### Case 1: All Three in Series
Resistors are connected one after another in a single path.
*   **Logic:** **1 $\Omega$ + 1 $\Omega$ + 1 $\Omega$**
*   **Equivalent Resistance:** **3 $\Omega$**

### Case 2: All Three in Parallel
All resistors are connected across the same two nodes.
*   **Logic:** $$\frac{1}{R_{eq}} = \frac{1}{1} + \frac{1}{1} + \frac{1}{1} = 3 \implies R_{eq} = \frac{1}{3} \Omega$$
*   **Equivalent Resistance:** **$\approx$ 0.33 $\Omega$**

### Case 3: Two in Series, Parallel with the Third
Two resistors are connected in series (**2 $\Omega$** branch), and this branch is parallel to the remaining resistor.
*   **Logic:** $$R_{eq} = \frac{R_{branch} \times R_3}{R_{branch} + R_3} = \frac{2 \times 1}{2 + 1} = \frac{2}{3} \Omega$$
*   **Equivalent Resistance:** **$\approx$ 0.67 $\Omega$**

### Case 4: Two in Parallel, Series with the Third
Two resistors are connected in parallel (**0.5 $\Omega$** equivalent), and this group is in series with the third resistor.
*   **Logic:** **0.5 $\Omega$ + 1 $\Omega$**
*   **Equivalent Resistance:** **1.5 $\Omega$**

---

## 4. List of All Unique Values
The possible equivalent resistances are:
1.  **3 $\Omega$**
2.  **1.5 $\Omega$**
3.  **0.67 $\Omega$** (**2/3 $\Omega$**)
4.  **0.33 $\Omega$** (**1/3 $\Omega$**)

---
