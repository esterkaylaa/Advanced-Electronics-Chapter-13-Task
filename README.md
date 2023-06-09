# Advanced-Electronics-Chapter-13-Task
Created by Ester Kayla Olivia (NIM : 21/476559/PA/20582). 

Advanced Electronics task based on chapter 13.

# Overview
To create this VHDL program for each element we need creating all entities, connection each of the component.

Structure of program
 * Computer.vhdl
    * cpu.vhdl * control_unit.vhdl * data_path.vhdl * ALU.vhdl
    * memory.vhdl * rom_128x8_sync.vhdl * rw_96x8_sync.vhdl

# Run the Program
  Using GHDL and GTKWave
  
  `ghdl -a --ieee=synopsys -fexplicit files.vhdl
   ghdl -e --ieee=synopsys -fexplicit files
  
