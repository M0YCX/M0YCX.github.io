---
title: RF Feedback Amplifier
categories: [Theory]
tags: [BJT, Feedback, Amplifier]
math: true
---

I've written a Jupyter Notebook in Python that mirrors the functionality of Wes Hayward's Feedback Amplifier calculator
(`fba08.exe` that is provided with his book _Experimental Methods in RF Design_) - following the math in his earlier book _Introduction to Radio Frequency Design_ (- a truely excellent book!).

See: [Feedback Amplifier](https://github.com/M0YCX/ycx_rf_notebooks/blob/master/Amplifiers/feedback/Feedback%20Amplifier.ipynb)

(the repo code runs in a Docker container and the content is then viewed via a web browser, see [README](https://github.com/M0YCX/ycx_rf_notebooks/blob/master/README.md)).

The code is a work-in-progress and needs some cleanup, but the resulting calculations match those in Wes's `fba08.exe` utility.

Here is a screenshot of it running:

![Screenshot Feedback Amplifier Notebook](/assets/images/2024-09/fba_notebook_screenshot.jpg)

and a screenshot from Wes's fba08.exe with the same parameters:

![Screenshot EMRFD fba08](/assets/images/2024-09/FBA -- Feedback Amplifier Analysis _001.jpg)

This was an interesting learning journey, focusing on Z, Y and Cascading ABCD Matrix Parameters and associated math.
These were the matrix representations of:

* The base spreading resistance,
* The degenerating complex impedance,
* The Hybrid-Pi model of the transistor (and complex $\beta$),
* The complex impedance of the feedback network,
* The output impedance matching transformer

and how the source and load impedances affect the output and input impedances of the amplifier.
