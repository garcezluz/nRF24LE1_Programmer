# nRF24LE1_Programmer
Arduino Programmer for Nordic - nRF24LE1

Upload the sketch to your Arduino (Nano v3.0) and connect SPI from Nano to nRF24LE1 board (see Schematic.pdf).

Programmer.exe:
Uploads .hex file into nRF24LE1 via Arduino
Usage: programmer.exe \\.\COM13 CMD filename.hex [NUPP] [RDISMB]
where CMD is d(dump), w (write)

This work is based on code https://github.com/DeanCording/nRF24LE1_Programmer - Thanks, DeanCording.
And also based on code https://github.com/polkabana/nRF24LE1_Programmer - Thanks, polkabana.
