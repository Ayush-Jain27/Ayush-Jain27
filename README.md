# Ayush Jain

**Digital design · Computer architecture · Embedded systems**

I'm interested in how computers work at every level, from the transistors in a datapath to the software that talks to a device. My projects span custom circuit design, processor RTL, FPGA systems, and low-level C.

I'm studying Computer Science and Astronomy at the University of Illinois Urbana-Champaign, with a minor in Electrical and Computer Engineering.

**I'm looking for internship and co-op opportunities in digital design, ASIC/SoC development, FPGA engineering, and embedded systems.**

[Portfolio](https://ayush-jain.dev) · [Repositories](https://github.com/Ayush-Jain27?tab=repositories)

## What I'm building

### [SIMT GPU](https://github.com/Ayush-Jain27/Simt-GPU)
**In progress · SystemVerilog · Computer architecture**

I'm building an eight-lane SIMT GPU to get hands-on with parallel processor design. The core brings together shared instruction control and per-lane computation in SystemVerilog.

The next goals are stronger verification, multi-warp execution, and FPGA bring-up. Hardware results and performance measurements are still ahead.

## Project showcases

### [RISC-V Datapath](https://github.com/Ayush-Jain27/riscv-datapath)
**Documentation showcase · Custom digital design**

I designed transistor-level schematics and layouts for a bit-sliced datapath in Cadence Virtuoso, including register-file, arithmetic, comparison, and selection blocks. I also worked on bringing custom blocks and synthesized logic together in the physical-design flow.

The showcase follows that work from individual cells to datapath integration, using original diagrams and design notes. It explains my contributions, identifies supplied infrastructure, and records the available verification evidence. Native design files are not published.

### [FPGA Audio Synthesizer & Visualizer](https://github.com/Ayush-Jain27/Real-Time-Audio-Synthesizer)
**Implementation showcase · FPGA design**

Alen Mathew Daniel and I built an FPGA audio system with microphone input, hardware effects, BRAM recording and looping, and HDMI visualization. Audio processing runs in hardware, while MicroBlaze handles control and interface state.

The repository includes the implementation and a walkthrough of the audio, memory, and video paths.

### [RISC-V Kernel Showcase](https://github.com/Ayush-Jain27/riscv-kernel)
**Documentation showcase · Systems programming**

This showcase looks at how a RISC-V kernel handles devices, interrupts, concurrent access, and storage. It covers UART, PLIC, RTC, VirtIO RNG and block drivers, condition variables, reader-writer locks, and NGFS.

The diagrams and notes focus on practical questions: who owns an I/O buffer, when a waiting thread can wake up, and how a device request reaches completion. The underlying source is unpublished. This repository explains the design; it does not provide a buildable kernel or verified runtime results.

## Tools I work with

| Area | Languages and tools |
| --- | --- |
| RTL and FPGA design | SystemVerilog, Verilog, Vivado, MicroBlaze |
| Custom and physical design | Cadence Virtuoso, Innovus, Synopsys Design Compiler, Calibre, SPICE |
| Systems programming | C, C++, Python, RISC-V assembly, Linux, GDB, Git |
