# STM32_BluePIill_Dynamic_indicatiion_second-float-_Proteus
STM32CubeIDE 1.10.1, Proteus 8.13
Library Installation :
Download or clone stm32 bluepill for proteus repository.
Open downloaded folder and copy BLUEPILL.IDX and BLUEPILL.LIB file from this folder.
Now open Proteus LIBRARY folder (check your proteus installation folder)
C:\Program Files (x86)\Labcenter Electronics\Proteus 8 Professional\DATA\LIBRARY

Now run proteus and open component Library.
Search for "STM32" or "BLUEPILL" and you can see your installed bluepill library.
Source code (Hex) :
Note: Select board as : STM32F103C6 in STM32CUBEMX or in STM32CUBEIDE. Only code compiled for STM32F103C6 is supported with this library.
Command to create hex file in CubeIDE:
arm-none-eabi-objcopy -O ihex ${ProjName}.elf ${ProjName}.hex
The NOT element replaced the NPN transistor on the cathodes, in this model Proteus does not support the use of transistors.

Перед початком роботи потрібно встановити необхідні бібліотеки BLUEPILL.IDX та BLUEPILL.LIB для Proteus за шляхом
C:\Program Files (x86)\Labcenter Electronics\Proteus 8 Professional\DATA\LIBRARY
При створенні проекту у CubeIDE необхідно обрати МК STM32F103C6
Для генерування hex файлу потрібно в налаштуваннях IDE додати команду
arm-none-eabi-objcopy -O ihex ${ProjName}.elf ${ProjName}.hex
Елементом NOT було замінено NPN транзистор на катодах, в цій моделі Proteus не підтримує використання транизисторів.
![153 6](https://user-images.githubusercontent.com/98404943/180651824-79b282c6-0f42-4c9e-ab22-63f1d5595723.png)
![0 068](https://user-images.githubusercontent.com/98404943/180651831-288c55f4-35aa-4ad5-8fff-4ce326bfc176.png)
