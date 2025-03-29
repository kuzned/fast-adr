# Fast Analog-to-Digital Recorder

*Analog-to-digital recorder (ADR) for data acquisition of single-event fast-flowing processes*

ADR is an electronic acquisition device that uses four 50 MSa/s flash analog-to-digital converters (ADCs) with time-interleaving to record an analog signal waveform at a total sample rate of 200 MS/s. The samples digitized by the ADCs are temporarily stored in a buffer memory before they are sent to a computer through the CAMAC bus interface.

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

The module was developed for the Institute of Electrophysics of the Ural Branch of the Russian Academy of Sciences to record the events occurring in high-current pulse devices, where typical process looks like an explosion of microsecond duration range.

The device was presented at the International Symposium on Problems of Modular Information Computer Systems and Networks (ICSNET'91).
