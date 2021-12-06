# 230D
A triple envelope follower project

The 230D Triple Envelope Follower is designed to replicate the functionality of the Buchla 230A module using modern construction techniques and readily available parts. It is primarily based on the original circuit designed by Don Buchla, with the following additions/alterations:

* Proper current limiting implemented for pulse output LEDs, increasing LED life and preventing crosstalk between channels
* Pulse/gate output voltages adjusted to 10V/5V
* Pulse outputs are buffered, protecting the passive pulse generation network from the effects of loading when stacking one output to multiple destinations
* Pulse outputs are designed to allow stacking of multiple outputs to a single input, whilst also being able to drive a floating input low.

The repository contains:

* KiCad project files
* Schematic and build/calibration notes as PDF files
* Bill of Materials in ODS and PDF format
* Interactive webpage for matching BOM items to PCB locations
