# Seiko uc-2000 reverse engineering

This is a project to restore of instruction set for Seiko UC-2000 and analogs. The goal of this project is to write first third-party application (even more - first program in more than 30 years) for these early smart watch.


**./rom**<br />
Contains 5 applications from the original ROM that came with the UC-2200. These files were taken from http://www.sigma957.org/datagraph.html

**./docs**<br />
Manuals and other documents.

**./ads**<br />
Scans of ads and magazine cuttings.

**./axasm**<br />
Assembler for Seico Cal. UW01, I used axasm by Al Williams (https://github.com/wd5gnr/axasm)

**./ucDisassembler**<br />
Very simple disassembler, but without which I would not have managed (Source code of applications from the ROM are in ./rom/disassembled)

**./apps**<br />
Programs written by me. Now there's Tetris and Watch face pack, see demo video

**./Transmitters**<br />
Firmware sources for the PC -> Watch wireless interface, and the application for Windows based on http://www.sigma957.org/datagraph.html
I will publish the device schemes a little later.

**Tetris demo**<br />
[![Video](https://img.youtube.com/vi/BHnZNJsGcyE/0.jpg)](https://www.youtube.com/watch?v=BHnZNJsGcyE)

**Face pack demo**<br />
[![Video](https://img.youtube.com/vi/W52tVbbM9_A/0.jpg)](https://www.youtube.com/watch?v=W52tVbbM9_A)
