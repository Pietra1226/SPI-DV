# SPI-Design & Verification
## GOAL: Using SystemVerilog to build a SPI module and verify it.
### Introduction
Serial Peripheral Interface Bus (SPI) is a synchronous serial communication interface specification for chip communication, mainly used in single-chip systems. Similar to I²C.

The advantages of SPI compared to I2C are that the transmission speed can be faster, full-duplex, and the length is not limited to one byte.

Full-duplex mode communication is a master-slave mode between a host and one or more slaves. The host is responsible for initializing the frame. This data transfer frame can be used for both reading and writing operations. The chip select line can select one from multiple slaves to respond to the host's request.

### SPI Configuration

### My SPI Project
