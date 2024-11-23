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

#### Synthesis RTL Schematic :
![image](https://github.com/user-attachments/assets/3f2ff8d4-a494-4ae0-bdc6-2c5cb98c0e09)


#### Area report:
![image](https://github.com/user-attachments/assets/efb0d046-7e3e-49b1-b169-21023b6d1d91)

#### Power Report:
![image](https://github.com/user-attachments/assets/c5c47482-dd7e-4b23-934c-73df6da0d4e9)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
