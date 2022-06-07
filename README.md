# phase-freq-estimation

## Motivation

Communication systems that rely on carrier frequencies to move the signal from baseband (centered around 0 Hz) to passband (centered around the carrier frequency) require two different frequency generators. Since they are two different devices, there are small diferences in the signal frequency and phase between the transmitter carrier frequency and the receiver carrier frequency. In order to improve the detection of the system, we can use methods to estimate both parameters. This project explores methods that improve the accuracy of the estimation of the frequency offset and the phase offset.

In order to identify the start of the signal of interest, different techniques are used, tipically including a preamble at the start of the signal that is detected by the receiver. This project explores changes to a simple preamble sequence that improve the preamble detection in the receiver.

This project is an extension of some lab content for a Communication Systems Electrical Engineering Elective.

The main file of the project is [Project Notebook](FinalProject.ipynb).
