# RTOS_ARM
For some prerequisite knowledge, please refer to the following tutorial link: https://github.com/Dungyichao/PeriodicScheduler_Semaphore and https://github.com/Dungyichao/STM32F4-LCD_ST7735s. We will use STM32F411VET6 Discovery Kit (Cirtex M4) accross this tutorial.

# 1. Getting Started

### 1.1 Create Project
Project --> New uVision Project.. --> Create a folder and enter the project name --> STMicroelectronics --> STM32F4 Series --> find STM32F411VETx 
### 1.2 Manage Run-Time Environment
CMSIS --> Select CORE <br />
Device --> Select Startup
### 1.3 Error Connecting to Board
You may encounter some problem when trying to flash your code from your PC to the board kit. You may need to check if the USB cable is good (some USB cable can only charge the board instead of transferring data). Then there might be driver problem which you may refer to the [link](http://www.keil.com/support/docs/3634.htm).


# 2. Board Support Package (BSP)
Create three file: STM32F4_RTOS_BSP.c, STM32F4_RTOS_BSP.h, main.c file. We will do something like making LED on the board blinking. Figuring out which port or pin for different LED can be refer to my tutorial [link](https://github.com/Dungyichao/PeriodicScheduler_Semaphore/blob/master/Reference/LED%20Light%20STM32f411%20Nucleo%20Code.pdf) , though the board is different. You can also refer to the  [STM32F411VE MCU Manual](https://www.st.com/resource/en/user_manual/dm00148985-discovery-kit-with-stm32f411ve-mcu-stmicroelectronics.pdf) and [STM32F411 Reference Manual](https://www.st.com/resource/en/reference_manual/dm00119316-stm32f411xc-e-advanced-arm-based-32-bit-mcus-stmicroelectronics.pdf).

You can find the code in Src folder. You may look through the following [link](https://librambutan.readthedocs.io/en/latest/lang/cpp/compoundbitwise.html) to know some symbol.




