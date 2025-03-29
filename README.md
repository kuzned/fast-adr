# Fast Analog-to-Digital Recorder

*Analog-to-digital recorder (ADR) for data acquisition of single-event fast-flowing processes*

ADR is an electronic acquisition device that could record an analog signal waveform using four 50 MSa/s flash ADCs with time-interleaving to reach the total sample rate of 200 MSa/s. The digitized samples then save to a buffer memory before being sent to a PC through the CAMAC bus controller.

## Main features

* Sampling rate: 200 MHz
* Sampling period: 5 ns
* Resolution: 6-bit
* Input dynamic range: 5V
* Input impedance: 50 Ohm
* Buffer RAM: 256 x 6-bit
* Main logic: ECL
* Interface: CAMAC bus
* Design: CAMAC module 2M-wide
* PCB: single-board 2-layer

## Background

The module was developed for Institute of Electrophysics of the Ural Branch of the Russian Academy of Sciences to record the events occurring in high-current pulse devices, where typical process looks like an explosion of microsecond duration range.

The device was presented on International Symposium on Problems of Modular Information Computer Systems and Networks (ICSNET'91).
