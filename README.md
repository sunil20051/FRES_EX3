## Simulation of Voltage controlled solar powered DC/DC converter under Closed loop Condition.

## AIM:

To simulate solar powered DC/DC boost converter using MATLAB Simulation for the output voltage control using P-I Controller.

## APPARATUS REQUIRED:
 MATLAB 2021 or above 
 
## Theory:

Closed-loop proportional-integral (PI) control is a widely used technique for regulating the output voltage in a DC-DC boost converter. It helps maintain a stable and accurate output voltage despite variations in input voltage, load current, and other operating conditions. Here's a step-by-step explanation of how closed-loop PI control works in a boost converter:
Components of the Control System:

Boost Converter: This is the DC-DC converter responsible for increasing the output voltage.
Reference Voltage (Vref): This is the desired or setpoint output voltage that you want to achieve and maintain.

Feedback System: The feedback system measures the actual output voltage (Vout) using a voltage sensor or divider network and provides this information to the controller.

Controller (PI Controller): The controller calculates the error (the difference between the reference voltage and the measured output voltage) and generates a control signal based on this error. The PI controller has two components

<img width="468" height="355" alt="image" src="https://github.com/user-attachments/assets/e593bb38-3026-486f-a97b-90aa3176633a" />



## CIRCUIT DIAGRAM:

<img width="1803" height="914" alt="Screenshot 2026-05-28 101000" src="https://github.com/user-attachments/assets/58735e57-8e31-4df9-ae0f-908562274362" />


## Procedure:

1.Open MATLAB

2.From Simulink library browser, pick the following components

a.Solar Panel
b.Current and voltage measurement
c.MOSFET, Diode, Inductor and capacitor
d.RLC series load
e.Constant, subtract, PI controller and PWM generator
f.Slider, Scope, display

3.Connect the Simulink library tools as shown in the circuit diagram.

4.Connect the slider tool with the constant block used for the reference value.

5.Set the parameters as per the required design.

6.Simulate the work for the different reference voltage by sliding the slider.

7.Note the input and output side parameters and tabulate it.

## OUTPUT:

<img width="1919" height="1199" alt="Screenshot 2026-05-28 101636" src="https://github.com/user-attachments/assets/2ee24913-152c-4c6a-acce-213cf352d71c" />


## RESULT: 

Thus, the closed loop output voltage control of solar powered dc/dc boost converter using PI controller is simulated using MATLAB.
    
