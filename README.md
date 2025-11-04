Paper Title: **“A Soft-switched Induction Cooking System with Reduced Switch Count and Independent Control for Multiple Loads”**

Paper id: **10062**

Authors: **Thoutreddy Deepthi Reddy and S Porpandiselvi**

The proposed “A Soft-switched Induction Cooking System with Reduced Switch Count and Independent Control for Multiple Loads” is simulated in PSIM software with an output voltage of 120 V and power rating of 629 W. The proposed inverter has the following benefits over existing topologies:
1.	An inverter configuration which can power three IH loads.
2.	 Independent power control for each load.
3.	High efficiency (96.1%) for wide range of power variations.
4.	Reduced number of devices per load.
5.	Wider range of ZVS.
6.	Easier extension for multiple loads by addition of another inverter leg
   
**Circuit description:**
The proposed inverter topology for multiple loads with cyclic ON and OFF control is presented. It consists of a dc source (Vdc) and four switching devices Sm, S1, S2 and S3. Dm, D1, D2 and D3 are the body diodes of MOSFETs. Cm, C1, C2 and C3 are the snubber capacitors. Three identical iron vessels are used as IH loads. R1, R2 and R3 are equivalent resistances and L1, L2 and L3 are equivalent inductances of IH coil-1, 2 and 3 with cooktops respectively. Cr1, Cr2 and Cr3 are the resonant capacitors for IH loads 1, 2 and 3 respectively. VL1, VL2 and VL3 are the voltages across the resonant loads 1, 2 and 3 respectively. IL1, IL2 and IL3 are the respective currents flowing through them.

**Working operation:**
The switching pulses Vgs1, Vgs2, Vgs3 and Vgsm for devices S1, S2, S3, and Sm respectively. The loads are controlled independently with cyclic ON and OFF control. The cyclic load control is applied at a low frequency of fL=1kHz. S1, S2 and S3 are operated at high frequency fsw = 43 kHz. TL= 1/fL where, TL indicates the time period of cyclic control duration. ta denotes the time duration for which load-1 and load-2 are powered. tb denotes the time duration for which load-2 and load-3 are powered. tc denotes the time duration for which load-1 and load-3 are powered. During tm, Sm is OFF and hence no load is powered.

**Applications of proposed converter:**
The proposed inverter is an excellent choice for multi-load domestic cooking applications
 
**Files uploaded:**
1)	Psim file-10068.psimch;
psim file to simulate the proposed inverter topology.
2)	Proposed inverter circuit diagram and simulation waveforms.pdf;
pdf file to show the circuit and simulation waveforms of proposed converter.
3)	Control logic diagram and description.pdf;
pdf file contains the generation of gating signals.


