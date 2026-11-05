# VUSV — Verification Using SystemVerilog

Academic reports on the design and class-based verification of sequential digital circuits at Manipal Institute of Technology.

## Project reports

| Project | Description | Report |
| --- | --- | --- |
| 16-bit synchronous up/down counter | Active-high synchronous reset, direction-controlled counting, and unsigned wraparound; directed and randomized stimulus with scoreboard checking. | [Read PDF](reports/16_Bit_Up_Down_Counter_Garv_Gupta.pdf) |
| JK flip-flop | Class-based verification of a JK flip-flop with synchronous reset, randomized inputs, a monitor, and a reference-model scoreboard. | [Read PDF](reports/JK_Flip_Flop_Group_Report.pdf) |

## Verification approach

Both reports use a modular SystemVerilog testbench built around transaction, generator, driver, monitor, and scoreboard classes. Typed mailboxes transfer transactions, while an interface and virtual interface handles connect the testbench to the DUT.

The PDFs include design methodology, verification architecture, waveform analysis, and SystemVerilog code listings. Standalone source files are not included in this repository.

## Simulation

- **Tools:** SystemVerilog, EDA Playground, and waveform viewing with EPWave.
- **Counter simulation:** [Open on EDA Playground](https://edaplayground.com/x/kLmW).
- Waveform evidence and verification scope are documented in the reports; no additional simulation runs or coverage measurements are claimed here.

## Credits

- **Counter report:** Garv Kishore Gupta.
- **JK flip-flop group report:** Shivansh Bose, Garv Kishore Gupta, Paarth Sud, and Priyangshu Agarwala.

Prepared for the Verification Using SystemVerilog internal assessment, 2026.
