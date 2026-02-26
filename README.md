Overview
This project focuses on the design, simulation, and physical layout of an Audio Input Preamplifier built around the LM324 operational amplifier. The circuit is designed to adapt and amplify low-level signals from various sources—such as radio-tape recorders and pick-ups—to a standardized level suitable for further processing.The design is optimized for a unipolar 18V power supply, utilizing a resistive divider and a 10 µF stabilization capacitor ($C_1$) to create a clean virtual ground ($V_r$) at 9V.
Key Specifications
Voltage Gain ($A$): Approximately 4 ($12$ dB).
Input Level: ~0.5 V.
Output Level: ~2 V.
Power Supply: 18V Unipolar.
Active Components: LM324 Quad Op-Amp.
Input Branches
The preamplifier features three distinct, switchable branches controlled by the SET parameter in simulation:
Radio-Magnetofon: Standard line-level adaptation.
Ceramic Pick-up: High-impedance source adaptation.
Magnetic Pick-up: Designed for low-level cartridge signals.
Project Structure
The project contains: 
Schematics: Circuit diagrams and electrical design./Layout: PCB design files, including TOP and BOTTOM copper layers./Simulations: Transient and Frequency (AC Sweep) analysis results./Proiect_docs: Full technical documentation (PDF format)./Bill_of_materials: Detailed list of all electronic components./Data_sheets: Reference documentation for the LM324 and other components.PCB_Manufacturing_Table: Gerber-related data and drill charts.Simulation & ResultsThe circuit was validated through extensive simulations:Frequency Analysis: Confirmed stability across the entire audio spectrum without significant attenuation.Transient Analysis: Demonstrated clean output waveforms with minimal distortion.Stability: The 10 µF capacitor ($C_1$) effectively filters noise and ripples from the virtual ground node, ensuring reliable operation.AuthorAndreea Zbranca Group: 432AUniversity "Politehnica" of Bucharest.
