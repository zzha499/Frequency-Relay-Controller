# Frequency-Relay-Controller

**Instructions for Running the Assignment on DE2-115 board**

To start running our assignment on an Intel (Altera) DE2-115 development board if the
provided project files do not work, please follow the steps below:
1. A .sof file is needed to program the device using Quartus Programmer tools.
2. Open NIOS build tools for Eclipse.
3. Create a new NIOS II application and BSP from Template using the provided
nios2.sopcinfo and then select the Hello World template.
4. Replace all contents of the hello_world.c with our main.c.
5. Copy the provided FreeRTOS folder into the project directory folder.
6. Compile and Build the program.
7. Right click on the project folder and then select Run as NIOS II Hardware.
