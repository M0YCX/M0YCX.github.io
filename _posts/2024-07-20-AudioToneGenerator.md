---
title: A Simple 1.2kHz Audio Tone Generator
categories: [Projects]
tags: [Signal-Generator]
math: true
image: /assets/images/2024-07/20240712_152615.jpg
excerpt: "A Simple 1.2kHz Audio Tone Generator, low distortion: -40dB, pk-pk: 140mV, with spice modelling and ugly construction."
---

From the "bible" Experimental Methods in RF Design [W7ZOI, KK7B, W7PUA].

This is intended to be used to generate a low distortion audio tone, to simulate a microphone input,
and to allow the signal to be traced through the audio input of a transmitter, e.g. to locate where
distortion may be being added to the signal.

## Spice Simulation

![spice simulation](/assets/images/2024-07/D20240710_1_2KHz_Sin_Osc_spice.png "Spice simulation of the low distortion audio 1.2KHz tone generator")

## Ugly Construction

![ugly build](/assets/images/2024-07/20240712_152615.jpg "Ugly style construction of the low distortion audio 1.2KHz tone generator")

## Results

![Second harmonic](/assets/images/2024-07/Osc%20screenshot.png "Oscilloscope showing harmonics of the 1.2KHz tone generator")

$$\Delta{}Y$$ (between the fundamental and the 2nd harmonic) = -40dB, pk-pk was 140mV.

This pretty much meets the design featured in EMRFD...
