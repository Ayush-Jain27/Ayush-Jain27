# Ayush Jain

**Digital design · Computer architecture · Embedded systems**

I build across the hardware–software boundary: transistor-level datapaths, parallel processor RTL, FPGA audio pipelines, and low-level systems software.

I study Computer Science and Astronomy at the University of Illinois Urbana-Champaign, with a minor in Electrical and Computer Engineering. My interests center on how processors and embedded systems work—from the circuits that hold state to the software that controls devices.

**Seeking internship and co-op opportunities in digital design, ASIC/SoC development, FPGA engineering, and embedded systems.**

[Portfolio](https://ayush-jain.dev) · [Explore my repositories](https://github.com/Ayush-Jain27?tab=repositories)

## In progress

### [SIMT GPU](https://github.com/Ayush-Jain27/Simt-GPU)
**Processor development · SystemVerilog · Eight-lane SIMT architecture**

Building an eight-lane GPU core to explore parallel execution and the hardware behind throughput-oriented computing. The project connects instruction execution, per-lane computation, and shared control in a custom RTL architecture.

**Development direction:** verification, multi-warp execution, and FPGA bring-up. These are ongoing goals; completed hardware deployment and performance results are not claimed.

## Engineering showcases

Selected implementation work presented through source, design explanations, and technical documentation. Each repository describes its own scope and available verification evidence.

### [RISC-V Datapath](https://github.com/Ayush-Jain27/riscv-datapath)
**Custom digital design · Documentation showcase**

Designed transistor-level schematics and layouts in Cadence Virtuoso for a bit-sliced datapath, including register-file, arithmetic, comparison, and selection structures. Worked on physical integration between custom blocks and synthesized logic.

The public showcase traces the design from reusable cells to datapath integration, with original diagrams, contribution boundaries, and verification notes. Native design databases and supplied processor infrastructure are excluded.

### [FPGA Audio Synthesizer & Visualizer](https://github.com/Ayush-Jain27/Real-Time-Audio-Synthesizer)
**FPGA system integration · Implementation showcase**

Co-developed an FPGA audio system combining microphone capture, hardware effects, BRAM recording and looping, and HDMI visualization. The architecture separates the streaming audio datapath from MicroBlaze-based control and interface state.

The repository presents the implementation and explains how audio, memory, control, and video fit together. Built with Alen Mathew Daniel.

### [RISC-V Kernel Showcase](https://github.com/Ayush-Jain27/riscv-kernel)
**Low-level systems · Documentation showcase**

A technical walkthrough of RISC-V kernel engineering: interrupt routing, device drivers, asynchronous I/O, synchronization, and persistent storage. Topics include UART, PLIC, RTC, VirtIO RNG and block devices, condition variables, reader–writer locks, and NGFS.

Original documentation and conceptual diagrams explain interface contracts, request lifetimes, and concurrency failure modes. The public repository contains explanatory material; the underlying kernel source is unpublished, and runtime validation is not established by the showcase.

## Technical toolkit

| Focus | Languages and tools |
| --- | --- |
| RTL and FPGA development | SystemVerilog, Verilog, Vivado, MicroBlaze |
| Custom and physical design | Cadence Virtuoso, Innovus, Synopsys Design Compiler, Calibre, SPICE |
| Systems programming | C, C++, Python, RISC-V assembly, Linux, GDB, Git |

I am drawn to engineering questions that connect these layers: where state belongs, how data moves, and how hardware and software agree on an interface.
