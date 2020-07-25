# stm32_micropython_mbed_bins
Drag-and-drop firmware MicroPython .bin files for Mbed-enabled STM32 boards

Make sure that your STM32 devboard is mbed OS enabled.  

Mbed-enabled boards will present as a disk drive when connected via USB to your computer.  Copy the .bin file that matches your board name to the USB disk drive via your preferred file explorer/manager/shell.

Your board will automatically reboot when flashing is complete.  Connect to the serial port of the board at the correct baud rate (115200 for most) and you should see the MicroPython prompt.  Press CTRL+D to soft-reset your board and you should see the board loading MicroPython.
