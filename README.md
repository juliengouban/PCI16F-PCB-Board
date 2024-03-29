# Project PIC16F board 

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)

This PCB is based on Microchip's PIC16F microcontroller. The PIC16F belongs to the PIC microcontroller family, renowned for its efficient RISC architecture and ease of programming.


Equipped with programmable flash memory, the PIC16F enables quick and easy firmware updates, simplifying the process of developing and maintaining electronic systems.
Its integrated EEPROM memory also offers non-volatile data storage, ensuring that crucial information is preserved even in the event of a power failure.
The PIC16F's numerous I/O pins facilitate interfacing with various external components, while its serial communication capabilities, such as I2C and UART, facilitate integration with other peripherals.
What's more, its interrupt management capabilities enable rapid response to real-time events, improving system responsiveness.


*Project duration: 2 days*


# Table of contents
- [Electronic diagram](#electronic-diagram)
- [PCB Design](#pcb-design)
  

## Electronic diagram

To program our pic16F22, we've added a 5-pin male connector that connects to the +5V, GND, RB6 and MCLR pins of the PIC16F microcontroller. This enables connection to the MPLAB kit and interfacing with the MLPAB ide developed by Microchip.

We've also added a green LED on the +5V to indicate that the board is powered up. We've also added an orange LED that flashes rapidly when the program is being transferred to the PIC16F.

Finally, we added two 14-pin female connectors to connect components to the PIC16F:

![alt text 1](PIC16F_picture/PIC16F_schema.png) 

The aim of the board was to make the design as small as possible: 23mm x 41mm. This keeps the cost of the board low: $12 at PCBWay.

To program the PIC16F board, you'll need an MPLAB kit to install the program.



## PCB Design

The PCB consists of two layers, Top Layer and Bottom Layer. We have a male connector at the top of the board for programming.

We use the GND, RB6 and MCLR pins connected to the MPLAB kit. We've added +5V to easily power the board once programmed.

We've also added two female connectors on either side of the PIC16F to easily connect components to it.

Here's the top layer view of the PCB:

![alt text 1](PIC16F_picture/pic16F_design.png) 



Here is a 3d view of the PCB:

![alt text 1](PIC16F_picture/pic16F_design2.png) 


## Arduino Factory

 * [More details on this project](https://arduinofactory.fr/carte-pcb-pic16f/)
  





