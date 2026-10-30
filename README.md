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

**1:** Write a script (in Python, or MATLAB) to evaluate the reconstructed field on a global grid (e.g., latitude $\lambda \in [-90^\circ, 90^\circ]$, longitude $\phi \in [-180^\circ, 180^\circ]$) and plot the following four cases:

**(a):** $$l = 2, \quad m = 1$$

**(b):** $$0 \le l \le 2, \quad 0 \le m \le l$$

**(c):** $$0 \le l \le 5, \quad 0 \le m \le l$$

**(d):** $$0 \le l \le 10, \quad 0 \le m \le l$$

**Note:** Solution for part (b) is attached as file delQ_l2.png for your script verification.

**2:** Plot the power spectrum and mention exclusively which degree and order contains the maximum power.

---

## Plotting & Submission Requirements

For each part (a)–(d):
* Display the spatial distribution on HAMMER projection.
* Use "bwr" colormap in python or use "bwr.m" file provided in matlab.
* Submit your source code alongside the generated plots.
---
#### **Course:** ES207 Earth Science Laboratory

