# Brushless DC Motor Control with MATLAB Simulink Electrical Simscape

## Project Media
![Dxxxxx](https://github.com/omerfaruktekin13/DroneEulerAnglesControlwithFeedback/blob/main/Media/SimulinkModel.png "Deneme ")
|:--:|
| *Simulink Diagram* |
![Dxxxxx](https://github.com/omerfaruktekin13/DroneEulerAnglesControlwithFeedback/blob/main/Media/ActuatorA.png "Deneme ")
| *Only Voltage FeedBack Control* |
![Dxxxxx](https://github.com/omerfaruktekin13/DroneEulerAnglesControlwithFeedback/blob/main/Media/ActuatorB.png "Deneme ") 
| *Voltage and Speed Feedback Control* |
![Dxxxxx](https://github.com/omerfaruktekin13/DroneEulerAnglesControlwithFeedback/blob/main/Media/Plot.jpg "Deneme ") 
| *Plot: Control at 5m* |

## Description
This project depicts a three-phase BLDC motor model using Simscape Electrical and investigates its back-EMF profile. I drive the motor by energizing one of the coil pairs using an inverter model. A three-phase inverter is basically a circuit that converts DC to AC current using three pairs of inverter switches, each corresponding to a phase. We need a Hall effect sensor to determine which sector the rotor is in. Commutation logic then uses the current sector to select the corresponding switching pattern. Furthermore, I added a PI feedback controller to control the motor speed. Lastly, I created a model of a PWM-controlled buck converter to control the speed of a BLDC motor.
## Tools and Languages
<a href="https://www.mathworks.com/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" alt="matlab" width="40" height="40"/> </a>
<p> * MATLAB 2023a </p>
<p> * Simulink </p>
<p> * Simscape Electrical </p>

## Installation
> 1. Download Eulerm.m and EulerSim.slx files.
> 2. Put these files into your MATLAB folder which is located in Documents.
> 3. Open the .m file and Simulink model. Evaluate the first section of the .m file to add drone characteristics into MATLAB workspace.
> 4. Play the Simulink model and you will see the control of the drone at 5 m with only voltage feedback control. Switch to Actuator B for voltage and speed feedback control.
## Open to Development
Please share your comments and ideas about the project with me. Thank you for your time.
