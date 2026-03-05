# PAM
ECE laboratory project implementing Pulse Amplitude Modulation (PAM) and demodulation using discrete analog components. Includes circuit design, hardware implementation, and CRO waveform analysis of the modulated and recovered signals.
Pulse Amplitude Modulation (PAM) – Hardware Implementation

Pulse Amplitude Modulation and Demodulation
1. Aim

To perform Pulse Amplitude Modulation (PAM) and demodulation.

2. Learning Outcome

After completing this experiment we will be able to understand how pulse amplitude modulation and demodulation can be accomplished.

3. Theory
Pulse Amplitude Modulation

Pulse amplitude modulation is a scheme which alters the amplitude of regularly spaced rectangular pulses in accordance with the instantaneous values of a continuous message signal. The amplitude of the modulated pulses represents the amplitude of the intelligence.

A train of very short pulses of constant amplitude and fast repetition rate is chosen. The amplitude of these pulses is made to vary in accordance with that of a slower modulating signal. The result is that of multiplying the train by the modulating signal. The envelope of the pulse height corresponds to the modulating wave.

The PAM wave contains upper and lower sideband frequencies besides the modulating and pulse signals.

Pulse Amplitude Demodulation

For demodulation of PAM waves, the signal is passed through a low pass filter having a cut off frequency equal to the highest frequency in the modulating signal.

At the output of the filter, the modulating signal along with a DC component is obtained.

PAM has the same signal to noise ratio as AM, therefore it is not commonly employed in practical circuits.

Hardware Setup
Components Used

Function Generator

Pulse Generator / Clock

Operational Amplifier

Diodes

Resistors

Capacitors

CRO (Cathode Ray Oscilloscope)

Circuit Diagram

Add your hardware circuit diagram here.

![Circuit Diagram](images/circuit_diagram.png)
Experimental Waveforms
Input Signal
![Input Signal](images/input_signal.png)
PAM Output
![PAM Signal](images/pam_signal.png)
Demodulated Signal
![Demodulated Signal](images/demodulated_signal.png)
Observations

Pulse amplitudes vary according to the instantaneous value of the message signal.

The envelope of the PAM waveform follows the modulating signal.

A low pass filter reconstructs the original signal during demodulation.

Repository Structure
PAM-Modulation-Demodulation
│
├── README.md
├── images
│   ├── circuit_diagram.png
│   ├── input_signal.png
│   ├── pam_signal.png
│   └── demodulated_signal.png
└── report
    └── pam_experiment.pdf
Author

Nehal Agarwal
B.Tech Electronics and Communication Engineering
