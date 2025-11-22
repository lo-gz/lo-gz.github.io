---
layout: page
title: Numerical results 
permalink: /results-mortech
---

## Comparison of the PGD solution with commercial software

Reference solution, computed on commercial FEM software

![reference_solution](./figures/u_6e6.gif)

PGD solution for order 1 linearisation, computed with 10 loading steps, 3 modes per step.
![pgd_solution](./figures/u_pgd.gif)

For $s=1.0$
![Comparison for s = 1.0](./figures/comp_u.svg)

Modes for the 10th loading step:
![Modes for the 10th increment](./figures/modes.svg)

## Series of results

### Comparison of results for the 3 orders -- 1 loading step

![ninc1-errVsOrder](./figures/ninc1_ord123/fullerrVsord.svg)

### Comparison of results for the 3 orders -- 10 loading steps

![ninc10-errVsOrder](./figures/ninc10_ord123/fullerrVsord.svg)

### Comparison of results for the 3 orders -- 100 loading steps

![ninc100-errVsOrder](./figures/ninc100_ord123/fullerrVsord.svg)

### Comparison of results for different number of loading steps -- order 1

![ord1-errVsNinc](./figures/nincs_ord1/fullerrVsninc.svg)

### Comparison of results for different number of loading steps -- order 2

![ord2-errVsNinc](./figures/nincs_ord2/fullerrVsninc.svg)

### Comparison of results for different number of loading steps -- order 3

![ord3-errVsNinc](./figures/nincs_ord3/fullerrVsninc.svg)
