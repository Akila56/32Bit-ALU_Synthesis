# 32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.
![image](https://github.com/user-attachments/assets/4b96c7db-9663-4143-9891-b6fb10cdf005)

#### Synthesis RTL Schematic :
![image](https://github.com/user-attachments/assets/22e852e7-07e8-4fcc-a6da-2c11a4c8c4a2)

#### Area report:
**![image](https://github.com/user-attachments/assets/2e674d3b-0fa8-4d10-b752-7c40a1af502a)
**
#### Power Report:
![image](https://github.com/user-attachments/assets/e7dd5c16-8b84-4f13-af40-6f9ac74aaa66)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
