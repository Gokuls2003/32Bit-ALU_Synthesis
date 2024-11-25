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

![Screenshot 2024-11-25 150051](https://github.com/user-attachments/assets/249d50db-4dc9-4f1b-a970-72434f2be753)


#### Area report:

![Screenshot 2024-11-25 150118](https://github.com/user-attachments/assets/d6f5194a-e7ac-4ec6-aa1c-ea5a2d0dfe25)


#### Power Report:

![Screenshot 2024-11-25 150215](https://github.com/user-attachments/assets/00777811-f24d-44b3-bf17-7d1ba6967d8d)


#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
