# ES 207: Earth Science Laboratory — Assignment II

##  Problem Statement
Develop a numerical code (e.g., in MATLAB or Python) to compute and visualize the heat flux variation $\Delta Q$, 
at the Earth's Core-Mantle Boundary (CMB). The visualization must utilize spherical harmonic expansion based on the provided Gauss coefficients.

---

## Dataset Description

The file **`dT_outer_spherical_harmonics_l10.txt`** is organized into four tab-separated columns without header lines:

| Column | Symbol | Description |
| :--- | :--- | :--- |
| **Col 1** | $l$ | Spherical harmonic degree  |
| **Col 2** | $m$ | Spherical harmonic order  |
| **Col 3** | $g_l^m$ | Cosine coefficient  |
| **Col 4** | $h_l^m$ | Sine coefficient  |

---
---
## Assignment Tasks

Write a script (in Python, or MATLAB) to evaluate the reconstructed field on a global grid (e.g., latitude $\lambda \in [-90^\circ, 90^\circ]$, longitude $\phi \in [0^\circ, 360^\circ]$ or $[-180^\circ, 180^\circ]$) and plot the following four cases:

1. **(a):** $$l = 2, \quad m = 1$$

2. **(b):** $$0 \le l \le 2, \quad 0 \le m \le l$$

3. **(c):** $$0 \le l \le 5, \quad 0 \le m \le l$$

4. **(d):** $$0 \le l \le 10, \quad 0 \le m \le l$$

---

## Plotting & Submission Requirements

For each part (a)–(d):
* Display the spatial distribution on HAMMER projection.
* Use "bwr" colormap in python or use "bwr.m" file provided in matlab.
* Submit your source code alongside the four generated map plots.
---
#### **Course:** ES207 Earth Science Laboratory

