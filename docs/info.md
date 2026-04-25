<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works
The full adder adds three 1-bit binary inputs: A, B, and Carry-in (Cin).
It produces two outputs: Sum and Carry-out (Cout).
The Sum output is generated using XOR logic, while Cout is generated when at least two inputs are high.
This circuit is commonly used in arithmetic units for binary addition in digital systems.

## How to test
To use this project, provide input values through ui_in[0], ui_in[1], and ui_in[2] for A, B, and Carry-in respectively.
Run the simulation using the provided testbench to verify the outputs.
The result appears on uo_out[0] as Sum and uo_out[1] as Carry-out.
You can test all input combinations to confirm the full adder truth table behavior.

## External hardware

No external hardware is required for this project.
The full adder design is fully implemented inside the ASIC logic using Tiny Tapeout input and output pins.
Inputs are provided through the dedicated input pins, and outputs are observed through the dedicated output pins.
Optional testing can be done using simulation tools such as Icarus Verilog and GTKWave.
