# Johnson Counter using Verilog

## Description
A Johnson counter is a sequential digital circuit made using flip-flops
with the inverted output of the last flip-flop connected to the input
of the first flip-flop.

## Working
A 4-bit Johnson counter produces the following sequence:

0000 → 1000 → 1100 → 1110 → 1111 → 0111 → 0011 → 0001 → 0000

## Files
- `johnson_counter.v` - Verilog design code
- `johnson_counter_tb.v` - Testbench
- `simulation/waveform.vcd` - Simulation output
- `simulation/waveform.png` - Waveform screenshot

## Tools Used
- Verilog HDL
- Icarus Verilog
- GTKWave

## Applications
Johnson counters are used in sequence generation, timing circuits,
frequency division, control circuits, and digital systems.