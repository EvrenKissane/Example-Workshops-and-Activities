## Superconducting Transmon

1. **Abstract Theoretical Physics**  
   A transmon is a nonlinear bistable superconducting resonator.  
   "nonlinear" - the resonance and modes depends on the amplitude  
   "bistable" - there are two frequencies where the resonance is stable  
   Measuring the resonance gives you the state, |0> or |1>.  
   The resonances defines the transition between them, which affects how well you can read the state.  

2. **Demonstrated Phenomenon**  
   Qubit resonance causes oscillations between the two states.  
   Readout discriminates the signals, which depend on the resonance.  
   Measured T1 (relaxation) & T2 (dephasing), and readout contrast informs you what error rates you will have to account for in the control pulses.  
   Gate fidelity: single qubit gates >99.9%; two qubit gates 98-99.9% depending on calibration.  

3. **Controlled Physics**  
   Shape and calibrate pulses and drives to flip, rotate, or entangle states without leaking energy or decohering.  
   Microwave pulses are used for X and Y rotations, and cross-resonance or parametric drives are used for entanglement.  
   What gate fidelities you can achieve determines how you should wire the chip, and how often to calibrate it.  

4. **Systematic Implementation**  
   Layout qubits on the chip: couplers, readout resonators, multiplexed readout, cryo-wiring, shielding, and filters.  
   "couplers" - connect two qubits  
   "readout resonators" - mechanism to read the resonance of the qubit  
   "multiplexed readout" - read multiple qubits at once  
   "cryo-wiring" - optimize the wires to run well at very low temperatures  
   "shielding" - reflect outside noise  
   "filters" - ignore noise and select the frequencies that you need to read out  
   Common layouts are square or hex nearest-neighbor, or ring layouts. There is new research on 3D structures.  
   Layout and control constraints define the resources needed to run programs.  

5. **Deployed Processor**  
   End-to-end fidelity and cycle time are the final metrics that combine the theory, demonstrations, control, and system design.  
   With calibrated gates and hardware in place, follow these steps:  
   (1) compile circuits to native pulses  
   (2) execute sequences  
   (3) read resonances to get outputs  
   (4) repeat with scheduled recalibration  

# Notes
**Challenges in Scaling**
- crosstalk (addressed via multiplexing)
- wiring complexity
- heat load from control lines & cryogenic electronics
- fabrication yield & materials.

**Vendors**
- IBM
- Rigetti
- Google Quantum
- Baidu
- Intel
- IQM