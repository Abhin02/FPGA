# FPGA Interfacing

This project is a set of all the files and documentation of the FPGA project work that was carried out in WEL Laboratory - IIT Bombay during Summer 2016.

## Aim
* To build and program a circuit that uses a CPLD controller to divide computations between two FPGA chips.
* To program Altera CPLD chip using a microcontroller which emulates the Altera USB Blaster. This would allow direct programming from Quartus II without the hassles of external hardware requirements, UrJTAG and the need to create Serial Vector files.

## Circuit Designs

We have added the Eagle files for the Krypton Board, an Altera Max V based development board that was designed earlier by WEL Laboratory. We used this board for testing and building the circuit. The files can be found under [eagle/Krypton/](eagle/Krypton/). There are two eagle files, a daughter card for housing the Max V CPLD IC and a main board for the development board peripherals, such as LEDs and switches.

The board we worked on has been designed under [eagle/main_circuit.sch](eagle/main_circuit.sch) and [eagle/main_circuit.sch](eagle/main_circuit.sch)


A detailed documentation of the project can be found in [report.pdf](report.pdf)
