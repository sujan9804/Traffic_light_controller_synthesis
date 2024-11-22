# Exp-6: Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

Synthesis RTL Schematic :


![WhatsApp Image 2024-11-22 at 21 52 32_f986f47e](https://github.com/user-attachments/assets/bd9ffcf9-2287-4b0a-a94e-280ae57f7553)



Area report:

![WhatsApp Image 2024-11-22 at 21 52 31_118fca2e](https://github.com/user-attachments/assets/117f6980-5dd8-4be1-90c9-f56c35e75e95)



Power Report:

![WhatsApp Image 2024-11-22 at 21 52 31_749211a9](https://github.com/user-attachments/assets/32e3f0d2-e433-40a4-9afd-d69a3f0e838c)




Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
