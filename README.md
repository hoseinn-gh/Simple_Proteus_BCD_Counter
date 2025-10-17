# Digital 0-99 Synchronous Counter

## Description

[cite_start]This is a Proteus project for a synchronous digital counter that counts from 00 to 99[cite: 3]. [cite_start]The design is based on a single 8-bit standard counter architecture rather than two separate BCD counters[cite: 3]. [cite_start]A dedicated combinational logic circuit calculates the tens and ones digits from the 8-bit binary value for display on two 7-segment units[cite: 3, 83]. [cite_start]All components are driven by a single, shared clock signal[cite: 3, 380].

## Features

* [cite_start]**Counting Range:** 00 to 99[cite: 3].
* [cite_start]**Bidirectional Counting:** Supports both **up-counting** (0 to 99) and **down-counting** (99 to 0)[cite: 3].
* [cite_start]**Control Inputs:** Includes **Enable**, asynchronous **Clear**, and parallel **Load** functionalities[cite: 3].
* [cite_start]**Automatic Rollover:** The logic automatically handles the transition from 99 to 0 when counting up, and from 0 to 99 when counting down[cite: 204, 253].
* [cite_start]**Synchronous Design:** The entire counter operates on a single, common clock signal[cite: 3, 380].

## Implementation Details

[cite_start]The counter is constructed from a chain of single-bit cells, each built with a D-type flip-flop (4013), multiplexers (74HC157), and logic gates[cite: 1, 77, 81]. [cite_start]The binary-to-BCD conversion logic is implemented using 4-bit adders (4008) to process the counter's 8-bit output[cite: 94].

## Software

The circuit is designed and simulated using **Proteus Design Suite**.
