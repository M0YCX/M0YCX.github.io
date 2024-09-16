---
title: Visualising the transistor Hybrid-Pi model with QUCS-S and ngspice
categories: [Theory, Modeling]
tags: [Amplifier, Hybrid-Pi, ngspice]
math: true
image: /assets/images/2024-09/ngspice-hybrid-pi-noccb.png
excerpt: Reproducing the transistor hybrid-pi model in QUC-S/ngspice and modelling the collector-base capacitance feedback (aka the Miller Effect)
---

Here I am reproducing the transistor hybrid-pi model in QUCS-S with ngspice.  I wanted to view the behaviour of the [Miller Effect](https://en.wikipedia.org/wiki/Miller_effect) of a transistor's intrinsic capacitances - specifically the Collector-Base capacitance on the model at radio frequencies.

This shows the basic hybrid-pi model with the collector-base capacitance disabled:-
![The Hybrid-Pi model without collector-base capacitance](/assets/images/2024-09/ngspice-hybrid-pi-noccb.png)
note the Y12 (reverse transfer admittance) parameters are all zero.  The igain plot pretty much matches the expected "ideal" plot of hybrid-pi $|\beta|$ I show in (Complex Beta of a Bipolar Transistor)[{% post_url 2024-07-22-BJTComplexBeta.md %}].

Here we enable the collector-base (_Ccb_) capacitance:-
![The Hybrid-Pi model with collector-base capacitance](/assets/images/2024-09/ngspice-hybrid-pi-ccb.png)
further reducing gain at high frequencies (in this case above 1MHz).
