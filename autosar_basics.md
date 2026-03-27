**UART:**
Universal Asynshronous Receive Transmit -> a HW module in the chip for serial communication without clock -> so, Async.
Using USB to UART converter chips, we connect to PC and get the serial logs printed, with specific baudrate set.
Voltage level: +/-3V

**RS232**
Recommended Standard 232
Higher voltage level, to drive high voltage devices.
UART can be converted to RS232 level using MAX232 chip, then can be connected via RS232 ports.
It is a electrical voltage standard. Kind of a medium

**JTAG**
Joint Test Action Group
It is also a HW module in the microcontroller
It is not related to UART, it is independent hardware module for debugging, separate lines are available in microcontroller which is connected to the external JTAG connector
