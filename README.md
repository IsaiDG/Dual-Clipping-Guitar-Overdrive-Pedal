# Dual-Clipping-Guitar-Overdrive-Pedal

## Overview
This pedal was based on Wampler Pedals' guitar overdrive circuit. It builds on the Walpler's diode clipping mechanism within the feedback loop of a TL082 op amp by adding a switchable hard clipping path outside of the opamp. This switching is done with a Triple Pole Double Throw (3PDT) footswitch with one pole illuminating an LED to indicate which switching mode is active.

The reason for the creation of this pedal was to learn AC analysis and design techniques before being officially taught these skills in my college courses. Also my current overdrive pedal broke so I needed a new one. Valueable technical skills were also learned in the creation of this pedal including software simulation through LTSpice, breadboarding, PCB design through KiCad, and soldering. 

## Concepts Learned and Applied
 - Diode Clipping (1N4148) within TL082 op amp feedback loop (Soft Clipping)
 - Diode Clipping after feedback loop (Hard Clippling)
 - Variable op amp gain
 - High/Low Pass filters
 - Coupling and Decoupling capacitors
 - DC bias
 - Variable tone control
 - Variable Volume control
 - 3PDT switching
 - Op amp Gain Bandwidth Product (GBP)

## Design and Devlopment Process
1. Circuit Design and Simulation: Developed and analyzed clipping circuits seperately in LTspice to investigate signal behavior. Imported real guitar files to see how circuit aurally affected real audio

2. Breadboard Prototyping: Realized circuit onto breadboard and verified bias voltage by comparing simulated behavior and multimeter readings. Troubleshooted issues including incorrect input and output terminals, uneven feedback loop voltages, and faulty components.

3. PCB Design: Full schematic made in KiCAD using 3PDT switch. Created PCB design and prepared the design for fabrication
 
4. Hardware Assembly (In Progress): Solder parts onto custom PCB

## Future Projects
As my first independent analog electronics project, this pedal established a foundation for more advanced hardware design. Future projects will build on these skills through more complex analog circuits, embedded systems, and digital signal processing. Potential improvements could include cleaning up the PCB layout, creating pedal case, and adding a bypass switching capability.
