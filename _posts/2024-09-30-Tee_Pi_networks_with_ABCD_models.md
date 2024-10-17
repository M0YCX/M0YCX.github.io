---
title: Modelling Tee and Pi networks using ABCD matrix models
categories: [Theory, Modeling]
tags: [ABCD, Networks, Tee, Pi]
math: true
image: /assets/images/2024-09/two-port-tee-pi-model.jpg
excerpt: Modelling Tee and Pi networks using ABCD matrix models, including an example chebyshev pi low pass filter.
---

In this notebook I have used ABCD Networks to describe individual components in Tee and Pi circuits, to build the circuit networks and then calculate their respective Immittances:-

[Notebook: two_port_nodes](https://github.com/M0YCX/ycx_rf_notebooks/blob/master/Math/two_port_nodes.ipynb)

This example shows a 3rd order Chebyshev filter with 80MHz cutoff, $Z_0=75\Omega$ - calculated for F=70MHz:-

![Screenshot of the Chebyshev 3rd order filter constructed from ABCD matrices](/assets/images/2024-09/two-port-tee-pi-model.jpg "Screenshot of the Chebyshev 3rd order filter constructed from ABCD matrices")

UPDATE: Added a spice analysis of the low pass filter to verify the results.
