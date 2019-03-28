# **Digital-Communications-Project**
Simulating the performance of different modulation schemes.
- [**BPSK**](#binary-phase-shift-keying-modulation-bpsk)
- [**QPSK**](#quadrature-phase-shift-keying-modulation-qpsk)
- [**FSK**](#frequency-shift-keying-fsk)
- [**QAM16**](#quadrature-amplitude-modulation-qam16)
- [**QAM64**](#quadrature-amplitude-modulation-qam64)

### **Binary Phase Shift Keying Modulation (BPSK)**
### Definition
**Binary Phase Shift Keying (BPSK)** is a two phase modulation scheme, where the 0's and 1's in a binary message are represented by two different phase states in the carrier signal: theta = 0 for binary 1 and theta = 180 degrees for binary 0.

### Parameters
```
Random Generator set size = 2
```
### Block Diagram
![BPSK Block Diagram](/BPSK/bpsk_diagram.PNG)
### At Transmitter Scatter Plot (before noise) and At Receiver Scatter Plot (after noise)
![BPSK Scatter Plot](/BPSK/fig.PNG)
### BER Diagram
![BER Diagram](/BPSK/ber_diagram.PNG)
## **With Raised Cosine Filter**
### Block Diagram
![BPSK with raised cosine Block Diagram](/BPSK/bpsk_diagram_raised_cosine.PNG)
### At Transmitter Scatter Plot (before noise) and At Receiver Scatter Plot (after noise)
![BPSK with raised cosine  Scatter Plot](/BPSK/fig_raised_cosine.PNG)
### BER Diagram
![BER Diagram with raised cosine](/BPSK/ber_diagram_rasied_cosine.png)
___
### **Quadrature Phase-Shift Keying Modulation (QPSK)**
### Definition 
**Quadrature Phase-Shift Keying Modulation ( QPSK )** is a form of Phase Shift Keying in which two bits are modulated at once, selecting one of four possible carrier phase shifts (0, 90, 180, or 270 degrees).

### Parameters
```
Random Generator set size = 4
Phase offset = pi/4
```
### Block Diagram
![QPSK Block Diagram](/QPSK/qpsk_diagram.PNG)
### At Transmitter Scatter Plot (before noise) and At Receiver Scatter Plot (after noise)
![QPSK Scatter Plot](/QPSK/fig.PNG)
### BER Diagram
![BER Diagram](/QPSK/ber_diagram.PNG)
## **With Raised Cosine Filter**
### Block Diagram
![QPSK with raised cosine Block Diagram](/QPSK/qpsk_diagram_raised_cosine.PNG)
### At Transmitter Scatter Plot (before noise) and At Receiver Scatter Plot (after noise)
![QPSK with raised cosine  Scatter Plot](/QPSK/fig_raised_cosine.PNG)
### BER Diagram
![BER Diagram with raised cosine](/QPSK/ber_diagram_raised_cosine.png)
___
## **Frequency Shift Keying (FSK)**
### Definition
**Frequency Shift Keying ( FSK )** is a frequency modulation scheme in which digital information is transmitted through discrete frequency changes of a carrier signal.

### Parameters
```
Random Generator set size = 2
M-ary number = 2
```
### Block Diagram
![FSK Block Diagram](/FSK/fsk_diagram.PNG)
### At Transmitter Scatter Plot (before noise) and At Receiver Scatter Plot (after noise)
![FSK Scatter Plot](/FSK/fig.PNG)
### BER Diagram
![BER Diagram](/FSK/ber_diagram.PNG)
## **With Raised Cosine Filter**
### Block Diagram
![FSK with raised cosine Block Diagram](/FSK/fsk_diagram_raised_cosine.PNG)
### At Transmitter Scatter Plot (before noise) and At Receiver Scatter Plot (after noise)
![FSK with raised cosine  Scatter Plot](/FSK/fig_raised_cosine.PNG)
### BER Diagram
![BER Diagram with raised cosine](/FSK/ber_diagram_raised_cosine.png)
___
## **Quadrature Amplitude Modulation (QAM16)**
### Definition
**Quadrature Amplitude Modulation ( QAM16 )** is a signal in which two carriers shifted in phase by 90 degrees (i.e. sin and cos) are modulated and combined. As a result of their 90 phase difference they are in quadrature and this gives rise to the name. Often one signal is called the In-phase or I signal, and the other is the quadrature or Q signal.

### Parameters
```
Normalization method = Average Power
Random Generator set size = 16
M-ary number = 16
```
### Block Diagram
![QAM16 Block Diagram](/QAM16/qam16_diagram.PNG)
### At Transmitter Scatter Plot (before noise) and At Receiver Scatter Plot (after noise)
![QAM16 Scatter Plot](/QAM16/fig.PNG)
### BER Diagram
![BER Diagram](/QAM16/ber_diagram.PNG)
## **With Raised Cosine Filter**
### Block Diagram
![QAM16 with raised cosine Block Diagram](/QAM16/qam16_diagram_raised_cosine.PNG)
### At Transmitter Scatter Plot (before noise) and At Receiver Scatter Plot (after noise)
![QAM16 with raised cosine  Scatter Plot](/QAM16/fig_raised_cosine.PNG)
### BER Diagram
![BER Diagram with raised cosine](/QAM16/ber_diagram_raised_cosine.png)
___
## **Quadrature Amplitude Modulation (QAM64)**
### Definition
**Quadrature Amplitude Modulation ( QAM64 )** is a signal in which two carriers shifted in phase by 90 degrees (i.e. sin and cos) are modulated and combined. As a result of their 90 phase difference they are in quadrature and this gives rise to the name. Often one signal is called the In-phase or I signal, and the other is the quadrature or Q signal. 

### Parameters
```
Normalization method = Average Power
Random Generator set size = 64
M-ary number = 64
```
### Block Diagram
![QAM64 Block Diagram](/QAM64/qam64_diagram.PNG)
### At Transmitter Scatter Plot (before noise) and At Receiver Scatter Plot (after noise)
![QAM64 Scatter Plot](/QAM64/fig.PNG)
### BER Diagram
![BER Diagram](/QAM64/ber_diagram.PNG)
## **With Raised Cosine Filter**
### Block Diagram
![QAM64 with raised cosine Block Diagram](/QAM64/qam64_diagram_raised_cosine.PNG)
### At Transmitter Scatter Plot (before noise) and At Receiver Scatter Plot (after noise)
![QAM64 with raised cosine  Scatter Plot](/QAM64/fig_raised_cosine.PNG)
### BER Diagram
![BER Diagram with raised cosine](/QAM64/ber_diagram_raised_cosine.png)
___