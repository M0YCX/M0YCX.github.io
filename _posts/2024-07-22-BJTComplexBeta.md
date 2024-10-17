---
title: Complex Beta of a Bipolar Transistor
categories: [Theory]
tags: [BJT, Beta]
math: true
image: /assets/images/2024-07/BJTComplexBeta.png
excerpt: A transistor's beta is complex at RF - The Hybrid-pi model
---

Reading Introduction to Radio Frequency Design by Wes Hayward [W7ZOI], and literally by only page 5 I'm wanting to plot a chart - to help me to understand the nature of Beta in Complex terms - from the math presented:

![Plot of complex beta for a bipolar transistor](/assets/images/2024-07/BJTComplexBeta.png "Plot of complex beta for a bipolar transistor")

$$
\beta(F) = \frac{\beta_0}{1 + j\beta_0 F/F_T}
$$

Notes:

* $\beta$ is Complex at RF
* The estimation: $\beta = F_T/F$ (solid red line above) only begins to be accurate well above $F_B$
* The phase angle of $\beta$ is $-45^\circ$ at $F_B$
* The phase angle of $\beta$ is $-90^\circ$ at $F_T$
