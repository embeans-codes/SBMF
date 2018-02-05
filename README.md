# SBMF
## Smart Bare Metal Framework

## Introduction
The intention of SBMF is to provide a rich set of proven drivers and code modules developed by core experts to reduce customer design-time. It simplifies the usage of microcontrollers, providing an abstraction to the hardware and high-value middlewares.

* SBMF is a free and open-source code library designed to be used for evaluation, prototyping, design and production phases.

* SBMF is code-size-optimized: Multiple ANSI-C compilers supported. Architecture-optimized by experts.
 
* SBMF is performance-optimized: DMA for communication. Interrupt-driven drivers. Chip-specific features in stacks.
* SBMF is low-power-optimized: Clock masking API, Sleep management API. Dynamic frequency and voltage scaling.
* SBMF is optimized for multicore, Asymetric Architectures : Multiple Coprocessors communication and functionality development.

## Architecture

SBMF consists of source code modules and applications demonstrating the use of these.

### Drivers 
This is composed of a driver.c and driver.h file that provides low level register interface functions to access a peripheral or device specific feature. The services and components will interface the drivers.

### Platforms
is a module type which provides more application oriented software such as a USB classes, FAT file system, architecture optimized DSP library, graphical library, etc.

### Components 
This is a module type which provides software drivers to access external hardware components such as memory (e.g. DataFlash, SDRAM, SRAM, and NAND flash), displays, sensors, wireless, etc.

### Boards
It contains mapping of all digital and analog peripheral to each I/O pin of differnt development kits.


