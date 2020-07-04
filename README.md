# RTOS_ARM
For some prerequisite knowledge, please refer to the following tutorial link: https://github.com/Dungyichao/PeriodicScheduler_Semaphore and https://github.com/Dungyichao/STM32F4-LCD_ST7735s. We will use STM32F411VET6 Discovery Kit (Cirtex M4) accross this tutorial.

# 1. Getting Started

### 1.1 Create Project
Project --> New uVision Project.. --> Create a folder and enter the project name --> STMicroelectronics --> STM32F4 Series --> find STM32F411VETx 
### 1.2 Manage Run-Time Environment
CMSIS --> Select CORE <br />
Device --> Select Startup


# 2. Board Support Package (BSP)
Create three file: STM32F4_RTOS_BSP.c, STM32F4_RTOS_BSP.h, main.c file. We will do something like making LED on the board blinking. Figuring out which port or pin for different LED can be refer to my tutorial [link](https://github.com/Dungyichao/PeriodicScheduler_Semaphore/blob/master/Reference/LED%20Light%20STM32f411%20Nucleo%20Code.pdf) though the board is different.



