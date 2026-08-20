## 8086 Assembly Digital Clock

This is a real-time digital clock built entirely in 8086 Assembly language. It was a project for my Microprocessors course to practice working directly with hardware and system interrupts.

### What It Does

The program communicates with the BIOS and DOS to fetch the current system time and date. It then changes the terminal interface to a blue background and prints the live time, date, and the current day of the week on the screen. The clock updates continuously without spiking CPU usage by utilizing a built-in delay interrupt.

### Run It

You will need an x86 emulator like DOSBox and an assembler like TASM.
Mount the directory in DOSBox, then run:
tasm saat.asm
tlink saat.obj
saat.exe
Press any key to exit the clock.

### Built With

- 8086 Assembly
