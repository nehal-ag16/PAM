# Pulse Amplitude Modulation and Demodulation
ECE laboratory project implementing **Pulse Amplitude Modulation (PAM) and demodulation** using discrete analog components. Includes **circuit design, hardware implementation, and CRO waveform analysis** of the modulated and recovered signals.



**1. Aim**

To perform Pulse Amplitude Modulation (PAM) and demodulation.

**2. Learning Outcome**

After completing this experiment we will be able to understand how pulse amplitude modulation and demodulation can be accomplished.

**3. Theory**

*Pulse Amplitude Modulation*

Pulse amplitude modulation is a scheme which alters the amplitude of regularly spaced rectangular pulses in accordance with the instantaneous values of a continuous message signal. The amplitude of the modulated pulses represents the amplitude of the intelligence.

A train of very short pulses of constant amplitude and fast repetition rate is chosen. The amplitude of these pulses is made to vary in accordance with that of a slower modulating signal. The result is that of multiplying the train by the modulating signal. The envelope of the pulse height corresponds to the modulating wave.

The PAM wave contains upper and lower sideband frequencies besides the modulating and pulse signals.

*Pulse Amplitude Demodulation*

For demodulation of PAM waves, the signal is passed through a low pass filter having a cut off frequency equal to the highest frequency in the modulating signal.

At the output of the filter, the modulating signal along with a DC component is obtained.

PAM has the same signal to noise ratio as AM, therefore it is not commonly employed in practical circuits.

**4. Hardware Setup**

Components Used:-

1) Function Generator
2) Pulse Generator / Clock
3) Operational Amplifier
4) Diodes
5) Resistors
6)Capacitors
7) CRO (Cathode Ray Oscilloscope)
8) Circuit Diagram

**5. Circuit Diagram**

<img width="379" height="325" alt="image" src="https://github.com/user-attachments/assets/b37ef5ad-d115-4511-bd85-c9339a2181c2" />

Circuit Diagram for generating a Pulse Amplitude Modulated Signal.

<img width="806" height="408" alt="image" src="https://github.com/user-attachments/assets/a0e4aa9e-5dcd-48b7-91b8-f4658e471060" />

Circuit Diagram to generate the corresponding demodulated PAM signal.

**6. Experimental Waveforms**

Input Signal
![Input Signal](images/input_signal.png)
PAM Output
![PAM Signal](images/pam_signal.png)
Demodulated Signal
![Demodulated Signal](images/demodulated_signal.png)

**7. Observations**

Pulse amplitudes vary according to the instantaneous value of the message signal.
The envelope of the PAM waveform follows the modulating signal.
A low pass filter reconstructs the original signal during demodulation.

**Author**
**~Nehal Agarwal**
**~B.Tech Electronics and Communication Engineering**
