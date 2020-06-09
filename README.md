# Team-Hermes-Senior-Design-Tremor-Damping
MATLAB and Python Model for the damping of physical tremors in patient's hands based on IMU measurements

## Actuator Model
**Actuator Model** contains the code for generating actuator model plots for our system, written in python. It is designed to
generate a plot based on inputted motor data. It is not a comprehensive motor selector, as that is outside 
the scope of this project. Instead, it is intended to show how a particular motor would align with our intended
actuation solution, a series of mechanical links that are actuated to dampen tremors

## Controller
**Controller** contains the matlab/simulink code that actually runs the simulation we designed. Our report contains the details
on the theory, but this is the code we used (along with the data) to generate our results. 

## Visualization
**Visulaization** contains the Blendr files and the code required to visualize our system's results in a more comfortable
form compared to the graph outputs of the MATLAB scripts

## How to Set Up the System: 

This system will require MATLAB/Simulink installation; no external libraries are needed as we relied on those provided in the student license. The controller MDL file contains inputs where the user can substitute their simulated tremor data and compare it against the norm healthy data; download and load this file in Simulink. As a sample, origx.csv is the healthy data, and tremorx.csv is the undamped simulated tremor data. Press Run in Simulink to simulate damping the tremor data, and click on any blue scope icon to display a particular waveform. 
