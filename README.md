# Cycloconverter-(1P to 1P)
Triac based cycloconverter laboratory prototype hardware design and drive.

Here conventional single phase to single phase cyclo-converter laboratory prototype hardware is design for testing purpose of convertional cyclo-converter circuit topology.
It is known to all that there are two type of circuit topology.

     1. Bridge type topology
     2. Mid point type topology
This example show how to drive a Mid point type cyclo-converter topology.

### Mid point type topology
Cycloconverter is used to convert a constant AC frequency into an adjustable AC frequency. Conventional mid-point cycloconverter shown in Fig. 1 uses two bidirectional TRIAC as switches and one center-tapped transformer. The output waveforms for mid-point cycloconverter always maintain a fixed ration i.e. fo = fi/3. The conversion techniques are shown in Fig. 2 and Fig. 3 for 25 Hz (fo = fi/2) and 16.67 Hz (fo = fi/3) frequency conversion of 50 Hz fuudamental respectively.

<img src="Image/image-3.png"> <img src="Image/image-5.png" width="490">
<img src="Image/image-2.png" width="500">

### Hardware Implementation
The hardware implementation can be divided into two parts, including: 

     1. Circuit designing part,
     2. Software part (coding).

### Circuit designing
To build the mid point type circuit, the following components are used:
      
      1. 12-0-12 V centre tapped transformer,
      2. BT136 (bidirectional TRIAC)
      3. MOC3021 (gate driving opto-coupler)
      4. 4N35 (Zero-cross detector opto-coupler)
      5. Arduino Uno Micro-controller.

The following figure shows the printed circuit board (PCB) design of the mid-point type cycloconverter.
<img src="Image/image-6.png" width="500">
