# James Anderson

**Hardware & systems engineer.** I take hardware apart to understand it, then
build things that work better — custom debug probes, board-level diagnostics,
and the software that drives them. My research is strictly white-hat:
read-only, defensive, and documented honestly, including the dead ends.

## What I do

- **Hardware security research & reverse engineering** — custom SWD/JTAG probe
  design (RP2040 + OpenOCD), SecureROM research, firmware analysis
- **Apple internals** — T2 DFU-mode USB enumeration, Lightning AV adapter
  SecureROM research, Smart Battery Case debug-console analysis
- **GPU & systems programming** — Metal compute, multi-GPU execution,
  memory-bounded tiled LLM inference in Objective-C
- **Board-level analysis** — UART debug bring-up, regulator and bus-level
  investigation

## Selected work

### [BareBoard](https://bareboard.org)
Free, open hardware-analysis platform — board-level teardowns, diagnostics
guides, and standard operating procedures.

### [Verum Bespoke Singularity](https://github.com/jamesmarcusanderson/verum-bespoke-singularity)
Multi-GPU LLM inference engine in Objective-C + Metal: custom mmap-backed GGUF
loader, runtime-generated MSL kernels, a declarative graph compiler, and a
bounded-memory tiled executor.

### [Tamarin](https://github.com/jamesmarcusanderson/tamarin)
Custom Pico SWD/JTAG probe (RP2040 + OpenOCD) bringing up the iPhone X (A11)
debug port.

### [Haywire](https://github.com/jamesmarcusanderson/haywire)
Reproduced the published checkm8 SecureROM dump of Apple's Lightning AV
Adapter (S5L8747) — read-only research, failures documented honestly.

### [Apple T2](https://github.com/jamesmarcusanderson/apple-t2)
Put a 2020 MacBook Air's T2 into DFU and decoded every USB identifier it
presents — enumeration only, no exploit work.

### [Smart Battery Case](https://github.com/jamesmarcusanderson/smart-battery-case)
Opened the A2070 Smart Battery Case's serial debug console, mapped all five
I2C buses, pulled live BMU telemetry — and documented exactly where RDP
level 2 stopped the investigation.

### [XB3](https://github.com/jamesmarcusanderson/xb3)
Board-level analysis of the Xfinity XB3 gateway (Arris TG1682, Intel Puma 6):
J3 UART boot capture and regulator research.

## Find me

- [LinkedIn](https://www.linkedin.com/in/jamesmarcusanderson)
- [bareboard.org](https://bareboard.org)

📍 Houston, TX
