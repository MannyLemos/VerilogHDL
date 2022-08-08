# VerilogHDL
Programming Verilog HDL on a DE1-SoC Development Kit using Quartus prime. This kit is built around the Altera System-on-Chip (SoC) FPGA.

## Project 1
A parameterized 4-bit and 30-bit counter, multiplexer, and seven segment decoder were instantiated and binded to a a top level module to create a multi mode counter driven by switches and keys.

## Project 2
A game was constructed allowing two users to compete to see who has a faster reaction time. This was acheived by designing a clock divider, a counter, a hexadecimal to binary-coded decimal translater a seven-segment display handler, a random numbergenerator, and a top-level module interfacing the submodules, as well as other auxiliary modules.

## Project 3
Two Digital Signal Processing systems were designed. First a Finite Impulse Response (FIR) filter was designed. The coefficients of this FIR filter were determined by analyzing an audio sample in matlab. Then an echo machine was developed. This DSP was implemented using shift registers by delaying samples ofan audio signal and then adding them to the current samples.

## Project 4
A controller was designed for the SDRAM memory chip on the DE1-SoC board. An SDRAM controller module from Altera was used, that provided all the essential and basic functions to interface with an SDRAM chip. A custom Platform Designer component was created, and then added to a Nios II based SOPC system. A piece of C code to test the functionality of the controller was written. Lastly, the operation of the Avalon interface to the SDRAM controller using Signal Tap Logic Analyzer was observed.

## Project 5
An Application Specific Instruction Set Processor (ASIP) for controlling a stepper motor was constructed. The processor will support instructions that can move the motor by a number of steps or half steps. The processor contains special purpose registers that keep track of the motor's current position, and allow the programmer to precisely control the time delay between steps. Circuitry was designed (using Verilog) that implements the datapath and control unit for the processor. A few simple programs were written in machine language for the newly built processor to test its functionality. 
