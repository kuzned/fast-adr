# Fast Analog-to-Digital Recorder

*Analog-to-digital recorder (ADR) for data acquisition of single-event fast-flowing processes*

Fast ADR is an electronic acquisition device using four 50 MSa/s flash analog-to-digital converters (ADCs) with time-interleaving sampling to record analog waveforms at a total sample rate of 200 MSa/s. The samples digitized by the ADCs then are temporarily stored in a buffer static memory before sending to a PC through the CAMAC bus controller.

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

The module was developed for the Institute of Electrophysics of the Academy of Sciences of the Soviet Union to acquire the events occurring in high-current pulse devices, where typical process looks like an explosion of microseconds range.

The device was presented at the International Symposium on Problems of Modular Information Computer Systems and Networks (ICSNET'91).
