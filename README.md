# Bachelor-Project
title: Development of User Interface to Digital Control Programmable Power Supplies

The project was developed specifically for HUF company and the steps to run the project are:

1. install the CANoe tool from Vector Informatik Gmbh: https://www.vector.com/int/en/support-downloads/download-center
2. insert the Vector license in the PC to open CANoe
3. create a new empty "Configuration" from File Window
4. import the entire project in the configuration:
   
   3.1. insert the network node "PS_2023", from Github -> Bachelor-Project -> main branch, in the Simulation Setup Window
   
   3.2. import the "system variables", from Github -> Bachelor-Project -> main branch, in the Environment Window
   
   3.3. add the GUIs: "powerSupply_2023", "logging", "input" and "raporting_instructions", from Github -> Bachelor-Project -> main branch, in the Panel Window

5. save the configuration
6. connect the programmable power supply(Konstanter or AimTTi) to the PC using an USB to RS232 converter cable
7. write, in the GUI, the serial port number through which the PC communicates with the power supply 
8. choose the power supply model
9. start the CANoe simulation
10. press the switch, from "powerSupply_2023" GUI, to turn on the output button from the power supply (to allow the voltage and current to flow to the power supply)
11. start setting values for voltage output and current limit output

Detailed explication of the project importing can be followed at https://github.com/alebele/Bachelor-Project/blob/aea89a82557a692003b33642c47e63bb534a0df5/Instructions%20how%20to%20import%20the%20PS_2023%20module%20in%20CANoe.docx.
