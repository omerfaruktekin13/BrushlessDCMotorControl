# Brushless DC Motor Control with MATLAB Simulink Electrical Simscape

## Project Media
![Dxxxxx](https://github.com/omerfaruktekin13/BrushlessDCMotorControl/blob/main/Media/SimulinkDiagram.png "Deneme ")
|:--:|
| *Simulink Diagram* |
![Dxxxxx](https://github.com/omerfaruktekin13/BrushlessDCMotorControl/blob/main/Media/ThreePhaseInverter.png "Deneme ")
| *Three Phase Inverter* |
![Dxxxxx](https://github.com/omerfaruktekin13/BrushlessDCMotorControl/blob/main/Media/BuckConverter.png "Deneme ") 
| *Buck Converter* |
![Dxxxxx](https://github.com/omerfaruktekin13/BrushlessDCMotorControl/blob/main/Media/CommunicationLogic.png "Deneme ") 
| *Communication Logic* |
![Dxxxxx](https://github.com/omerfaruktekin13/BrushlessDCMotorControl/blob/main/Media/SensorSystem.png "Deneme ") 
| *Sensor System* |

## Description
This project depicts a three-phase BLDC motor model using Simscape Electrical and investigates its back-EMF profile. I drive the motor by energizing one of the coil pairs using an inverter model. A three-phase inverter is basically a circuit that converts DC to AC current using three pairs of inverter switches, each corresponding to a phase. We need a Hall effect sensor to determine which sector the rotor is in. Commutation logic then uses the current sector to select the corresponding switching pattern. Furthermore, I added a PI feedback controller to control the motor speed. Lastly, I created a model of a PWM-controlled buck converter to control the speed of a BLDC motor.
## Tools and Languages
<a href="https://www.mathworks.com/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" alt="matlab" width="40" height="40"/> </a>
<p> * MATLAB 2023a </p>
<p> * Simulink </p>
<p> * Simscape Electrical </p>

## Installation
> 1. Download ThreePhaseBLDC.slx file.
> 2. Put these files into your MATLAB folder which is located in Documents.
> 3. You can change the properties of the Simscape Electrical Components to analyze effects of them in thermal, speed, and force.

## Open to Development
Please share your comments and ideas about the project with me. Thank you for your time.
