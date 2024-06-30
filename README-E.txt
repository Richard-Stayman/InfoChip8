InfoChip8 v0.1J Release Notes
Copyright (c) 2005 Jay's Factory

■ Introduction

InfoChip8 v0.1J is a CHIP-8 emulator that runs on Win32.
It is characterized by its high speed and portability.

■ Installation

(1) Extract the archive InfoChip801.zip

(2) Copy the executable file ./InfoChip801/bin/InfoChip8.exe to a suitable location

(e.g. c:\cygwin\usr\local\bin)

(3) Set the copy destination (e.g. c:\cygwin\usr\local\bin) in the environment variable PATH

[Control Panel] - [System] - [Advanced Settings] - [Environment Variables]

■ How to use

(1) Type the following from the command line

$ InfoChip8 [ROM file name (e.g. Pong.ch8)]

(2) Or drag and drop the ROM file onto the executable file InfoChip8.exe

(3) To exit, click [x]

■ Controls

The keys are mapped as follows.

Original　|1|2|3|C|　　remapped　　|1|2|3|4|
　　　　　　|4|5|6|D|　　　　　　　　 |Q|W|E|R|
　　　　　　|7|8|9|E|　　　　　　　　 |A|S|D|F|
　　　　　　|A|0|B|F|　　　　　　　　 |Z|X|C|V|

■ Specifications

□ Memory
　- ROM file (200H - F10H)
　- Hexadecimal font (F10H - F60H)

□ Registers
　- Data registers (V0 .. VF)
　- Address register (I)
　- Timers (delay, sound)
　- Stack (16-bits)

□ Graphics
- Sprites (CHIP-8 mode: 8 x 1 to 15)
- Collision flags
- Hex font

□ Instruction set
- CHIP-8 instructions (assignment, arithmetic, conditional branching, subroutines, sprites, etc.)

□ Keyboard
- Hexadecimal keyboard

■ How to build

To generate a binary from the source, do the following:

□ Preparation

(1) When installing Cygwin, check the following:

All + Devel + gcc: C, C++, Fortran compilers
All + Devel + gcc-mingw: Mingw32 support headers and libraries for GCC

(2) Download and extract the following file:

DirectX for MinGW
http://www.libsdl.org/extras/win32/common/directx-devel.tar.gz

(3) Copy include files and library files

$ cp ./include/*.h /usr/i686-pc-mingw32/include
$ cp ./lib/*.a /usr/i686-pc-mingw32/lib

□ Before building

(4) Extract the archive InfoChip801.zip

(5) Move to the directory ./InfoChip801/src/win32

$ cd ./InfoChip801/src/win32

(6) To build

$ make clean
$ make

[EOF]
