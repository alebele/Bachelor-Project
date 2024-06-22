# Bachelor-Project
title: Development of User Interface to Digital Control Programmable Power Supplies

how to run the project:

1. install the CANoe tool from Vector Informatik Gmbh: https://www.vector.com/int/en/support-downloads/download-center
2. insert the Vector license in the PC
3. open the CANoe tool and import the entire project:
   
   3.1. **insert the network node "PS_2023"**, from "to_import" folder, in the Simulation Setup Window
   
   3.2. **import the "system variables"**, from "to_import" folder, in the Environment Window
   
   3.3. **add the GUIs: "powerSupply_2023", "logging", "input" and "raporting_instructions"**, from "to_import" folder, in the Panel Window
   
5. connect the programmable power supply(Konstanter or AimTTi) to the PC using an USB to RS232 converter cable
6. write, in the GUI, the serial port number through which the PC communicates with the power supply 
7. choose the power supply model
8. start the CANoe simulation
9. press the switch, from "powerSupply_2023" GUI, to turn on the output button from the power supply (to allow the voltage and current to flow to the power supply)
10. set values for voltage output and current limit output

description of the project:

This project was thought within the SC HUF ROMANIA SRL company having the objectives of optimizing and
streamlining fundamental functionalities for the test teams.

The main goal was to enable a digital option of controlling the programmable power supply parameters,
which are the voltage and current limit, through a graphical user interface created with the
CANoe tool, thus eliminating the need for manual adjustments of the parameters through the
physical interface of the power supply. 

This digital control provides semi-remote management of the power supply that is connected to the PC or to a remote setup. 
Thus, the testers can adjust the voltage and current limit of the power supply from distance, when they need to work from home.

Within the project, the following actions can be performed:
- logging: the process through which the voltage and current consumption, along with the simulation
time, are stored in the log file
- reporting: feature that generates a graph showing the changes of voltage and
current values in real-time. It facilitates visual analysis.
- input panel control: this feature allows users to set initial and target values for
voltage, specifying in which way and when the target should be reached. This is helpful in test
scenarios where the power supply needs to adjust its voltage value at a certain time or after a certain
period of time in order to enter a different operational branch.

The project has been successfully configured for two power supplies models: Konstanter and AimTTi. 
