# ELC325-Matlab-Simulink-Project
Simulation of the performance of different modulation schemes, BPSK, QPSK, FSK, QAM(16-64) in an AWGN environment.

## To reproduce the Figures
1. Open matlab
2. Choose simulink from the toolbar
3. Open the desired model
4. Write bertool in the command window and set Eb/N0 -10:1:10 in theoritcal and monte carlo
5. Press browse and choose the model.slx
6. Ber variable Name = ber
7. Press plot in theoritcal and run in monte carlo

## Modulation Schemes

### BPSK Modulation Scheme
Binary Phase Shift Keying (BPSK) is a two phase modulation scheme, where the 0’s and 1’s in a binary message are represented by two different phase states in the carrier signal: θ=0∘ for binary 1 and θ=180∘ for binary 0.

#### BER performance figure [BER versus Eb/No ranging from -10 to 10 dB]
<p align="center">
  <img width="500" height="500" src="https://i.ibb.co/hBpD6W3/BER.png">
</p>
  <h4> Scatter plot of the symbols </h4>
<p align="center">
  <img src="https://i.ibb.co/QJqKvXV/Digrambefore-AWGN.png" height="400" width="400"> <img src="https://i.ibb.co/TqV12QC/Digram-After-AWGN.png" height="400" width="400">
</p>


### QPSK Modulation Scheme
Quadrature Phase Shift Keying (QPSK) is type of phase shift keying. Unlike BPSK which is a DSBCS modulation scheme with digital information for the message, QPSK is also a DSBCS modulation scheme but it sends two bits of digital information a time (without the use of another carrier frequency).
The amount of radio frequency spectrum required to transmit QPSK reliably is half that required for BPSK signals, which in turn makes room for more users on the channel.

#### BER performance figure [BER versus Eb/No ranging from -10 to 10 dB]
<p align="center">
  <img width="500" height="500" src="https://i.ibb.co/QF5LFNM/BER.png">
</p>
  <h4> Scatter plot of the symbols </h4>
<p align="center">
  <img src="https://i.ibb.co/CV7JLkX/Diagram-Before-AWGN.png" height="400" width="400"> <img src="https://i.ibb.co/B3bN0RL/Diagram-After-AWGN.png" height="400" width="400">
</p>



### FSK Modulation Scheme
Frequency-shift keying (FSK) is a method of transmitting digital signals. The two binary states, logic 0 (low) and 1 (high), are each represented by an analog waveform. Logic 0 is represented by a wave at a specific frequency, and logic 1 is represented by a wave at a different frequency. A modem converts the binary data from a computer to FSK for transmission over telephone lines, cables, optical fiber, or wireless media.

#### BER performance figure [BER versus Eb/No ranging from -10 to 10 dB]
<p align="center">
  <img width="500" height="500" src="https://i.ibb.co/TB7rVxb/BER.png">
</p>
  <h4> Scatter plot of the symbols </h4>
<p align="center">
   <img src="https://i.ibb.co/GMvhRQK/Diagram-Before-AWGN.png" height="400" width="400"><img src="https://i.ibb.co/6PG6c6b/Diagram-After-AWGN.png" height="400" width="400">
</p>


### QAM Modulation Scheme
QAM (quadrature amplitude modulation) is a method of combining two amplitude-modulated (AM) signals into a single channel, thereby doubling the effective bandwidth. QAM is used with pulse amplitude modulation (PAM) in digital systems, especially in wireless applications.
In a QAM signal, there are two carriers, each having the same frequency but differing in phase by 90 degrees (one quarter of a cycle, from which the term quadrature arises). 

### QAM16

#### BER performance figure [BER versus Eb/No ranging from -10 to 10 dB]
<p align="center">
  <img width="500" height="500" src="https://i.ibb.co/k8zbByj/BER.png">
</p>
  <h4> Scatter plot of the symbols </h4>
<p align="center">
  <img src="https://i.ibb.co/ZxNqq4X/Before-AWGN.png" height="400" width="400"> <img src="https://i.ibb.co/jZXndvm/After-AWGN.png" height="400" width="400">
</p>



### QAM64

#### BER performance figure [BER versus Eb/No ranging from -10 to 10 dB]
<p align="center">
  <img width="500" height="500" src="https://i.ibb.co/wJrbgNq/BER.png">
</p>
  <h4> Scatter plot of the symbols </h4>
<p align="center">  
  <img src="https://i.ibb.co/Y833qz3/Before-AWGN.png" height="400" width="400"> <img src="https://i.ibb.co/nDwykJ6/After-AWGN.png" height="400" width="400">
</p>

