# Micro Controller Design

8-bits general purpuse Micro-controller design including ALU, flags, program counter and support for conditional jumps. I created this project after learning about the makeup of a cpu from one of my hardware courses.
- Logisim (logic circuit design application)

## Development Environment:
1. Download Logisim http://www.cburch.com/logisim/ and install it on your pc
2. Clone the repository:
``` > git clone https://github.com/Ron-Ash/MicroControllerProject```
3. Open ```MicrocontrollerProjectFinalCircuit.circ``` in Logisim
4. Within the circuit find ![image](https://user-images.githubusercontent.com/37012505/214511693-1b557240-c8ff-4790-aa29-f896ee035ae7.png)
5. Press the "clear program memory" button on and off to clear the program memory
6. To write a new program into the cpu: (upto 8 assembly instructions)
    For each assembly instruction:
    1. Set the "Program location" buttons to the desired binary number (0-7) and then press the "SET" button
    2. Look in the ```MicrocontrollerOpCodeLibrary.xlsx``` file to find the desired assembly instructions and set the matching buttons accordingly (if the value in teh excel file is not 0 or 1 it means that its user input)
    3. Press the "write to program memory" button on and off to write the instruction into the program memory
7. Click on Simulate > Ticks Enabled (change ticks frequency to see how the cpu works better) to start the simulation (click again to stop)
8. Either look at the RAM or the console outputs to visually see what instructions and values are in the cpu:
![image](https://user-images.githubusercontent.com/37012505/214517156-8079012e-8f34-4475-949a-9282afcb8030.png)
![image](https://user-images.githubusercontent.com/37012505/214517304-78fa0dbc-b6b0-49b5-8930-2235489d80a0.png)
