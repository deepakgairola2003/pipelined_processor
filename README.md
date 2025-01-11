# pipelined_processor
This repository contain the verilog files of MIPS32 pipelined processor. <br>
I have made this project as a part of nptel course on hardware modelling using verilog. <br>
We have pipelined the main processes into 5 stages namely Instruction fetch(IF), Instruction decode (ID), Execution (EXE), Memory Access (MEM), Register Write Bank (WB) and used two clock clk1 and clk2.  <br>

processor.v contains the code for the datapath <br> 
processortb.v contains testbench with an example. <br>
The waveform is shown in waveform of pipelined processor <br>
Images of datapath and explanation of various instructions as well as architecture is present in 'Images' file

To run use these command in terminal <br> 
<ol>
<li>"iverilog -o mips.vcd processortb.v" <br>
<li>"vvp mips.vcd" <br>
<li>"gtkwave mips.vcd" <br>
</ol>
