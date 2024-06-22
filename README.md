# Bachelor-Project
title: Development of User Interface to Digital Control Programmable Power Supplies

how to run the project:

1. install the CANoe tool from Vector Informatik Gmbh: https://www.vector.com/int/en/support-downloads/download-center
2. insert the Vector license in the PC
3. open the CANoe tool and import the entire project:
   
   3.1. **insert the network node "PS_2023"**, from Github->Bachelor-Project->main branch, in the Simulation Setup Window
   
   3.2. **import the "system variables"**, from Github->Bachelor-Project->main branch, in the Environment Window
   
   3.3. **add the GUIs: "powerSupply_2023", "logging", "input" and "raporting_instructions"**, from Github->Bachelor-Project->main branch, in the Panel Window
   
5. connect the programmable power supply(Konstanter or AimTTi) to the PC using an USB to RS232 converter cable
6. write, in the GUI, the serial port number through which the PC communicates with the power supply 
7. choose the power supply model
8. start the CANoe simulation
9. press the switch, from "powerSupply_2023" GUI, to turn on the output button from the power supply (to allow the voltage and current to flow to the power supply)
10. start setting values for voltage output and current limit output
