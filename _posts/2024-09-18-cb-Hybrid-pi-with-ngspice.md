---
title: Visualising the common-base transistor Hybrid-Pi model with QUCS-S and ngspice
categories: [Theory, Modeling]
tags: [Amplifier, Hybrid-Pi, ngspice]
math: true
image: /assets/images/2024-09/ngspice-cb-hybrid-pi-nomillercap.png
excerpt: Reproducing the common-base transistor hybrid-pi model in QUC-S/ngspice and modelling the collector-base capacitance feedback (aka the Miller Effect)
---

In this one we look at the common-base spice model and show the miller-effect on current gain.

This shows the common-base hybrid-pi model with the collector-base capacitance disabled:-
![The common-base Hybrid-Pi model without collector-base capacitance](/assets/images/2024-09/ngspice-cb-hybrid-pi-nomillercap.png)

this is pretty close to the prediction made here for alpha $\alpha$:-
![Plot of the Hybrid-Pi common-base alpha](/assets/images/2024-09/hybrid-pi-cb-alpha-plot.png)

for a common-base amplifier:-

$$
\alpha = \frac{\beta}{(\beta + 1)}
$$

Here we enable the collector-base (_Ccb_) capacitance:-
![The Hybrid-Pi model with collector-base capacitance](/assets/images/2024-09/ngspice-cb-hybrid-pi-millercap.png)
