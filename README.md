# Ayush Jain

**Digital design · Computer architecture · Embedded systems**

I build across the hardware–software boundary: transistor-level datapaths, parallel processor RTL, FPGA audio pipelines, and low-level systems software.

I study Computer Science and Astronomy at the University of Illinois Urbana-Champaign, with a minor in Electrical and Computer Engineering. My interests center on how processors and embedded systems work—from the circuits that hold state to the software that controls devices.

**Seeking internship and co-op opportunities in digital design, ASIC/SoC development, FPGA engineering, and embedded systems.**

[Portfolio](https://ayush-jain.dev) · [Explore my repositories](https://github.com/Ayush-Jain27?tab=repositories)

## Selected work

### [RISC-V Datapath](https://github.com/Ayush-Jain27/riscv-datapath)
**Transistor-level design → physical integration**

Designed custom schematics and layouts in Cadence Virtuoso for a bit-sliced datapath, including register-file, arithmetic, comparison, and selection structures. Worked on integrating custom blocks with synthesized logic through timing and physical interfaces.

The public showcase documents my implementation and physical-design work, distinguishes supplied processor infrastructure, and describes the available verification evidence.

### [SIMT GPU](https://github.com/Ayush-Jain27/Simt-GPU)
**Parallel architecture → SystemVerilog RTL**

An eight-lane SIMT GPU core written in SystemVerilog, exploring how multiple execution lanes fit within a processor architecture.

### [FPGA Audio Synthesizer & Visualizer](https://github.com/Ayush-Jain27/Real-Time-Audio-Synthesizer)
**Streaming audio → hardware effects → HDMI visualization**

Co-developed an FPGA system combining microphone capture, audio effects, BRAM recording and looping, and HDMI visualization. The design separates the hardware audio pipeline from MicroBlaze-based control and interface state.

Built with Alen Mathew Daniel.

### [RISC-V Kernel Showcase](https://github.com/Ayush-Jain27/riscv-kernel)
**Interrupts → device I/O → synchronization → storage**

A documentation-only walkthrough of a RISC-V operating-system project, covering UART, PLIC, RTC, VirtIO RNG and block devices, condition variables, reader–writer locks, and NGFS.

The public material explains interfaces and failure modes through conceptual diagrams and technical notes. Kernel source is unpublished; the showcase does not claim a reproducible build or verified runtime results.

## Technical toolkit

| Focus | Languages and tools |
| --- | --- |
| RTL and FPGA development | SystemVerilog, Verilog, Vivado, MicroBlaze |
| Custom and physical design | Cadence Virtuoso, Innovus, Synopsys Design Compiler, Calibre, SPICE |
| Systems programming | C, C++, Python, RISC-V assembly, Linux, GDB, Git |

I am drawn to engineering questions that connect these layers: where state belongs, how data moves, and how hardware and software agree on an interface.
